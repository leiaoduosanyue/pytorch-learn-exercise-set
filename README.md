# pytorch-learn-exercise-set
本人通过学习动手学习深度学习这本书后，跟着书本写出的基于pytorch的练习集合  
在热狗识别这个文件中，各位需要自行下载 hotdog 训练集    

此处列出需要的库，各位需看看自己是否安装过  
%matplotlib inline  
import torch  
from torch import nn, optim  
from torch.utils.data import Dataset, DataLoader  
import torchvision  
from torchvision.datasets import ImageFolder  
from torchvision import transforms  
from torchvision import models  
import os  
import sys  
sys.path.append("..")   
import d2lzh_pytorch as d2l  
device = torch.device('cuda')   

各位可以去看看这本书 https://tangshusen.me/Dive-into-DL-PyTorch/#/   
我文件中的d2lzh_pytorch就是从这个网站中下载出来的，上述的 hotdog 的训练集也是如此  


此库应该会持续更新中，虽然我还是个萌新，但是还会持续学习下去，直到可以独立写出自己的ai
