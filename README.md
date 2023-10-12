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
