---
sort: 2
---

# Python

## 安装

- Windows OS
1. Anaconda + vscode

直接引用相关教程：[教程](https://blog.csdn.net/Xuanqing_C/article/details/123973103)

2. WSL + Anaconda + vscode

- Unubtu OS

- Mac OS







# python 读取Gaia星表的 .fits 文件 并作图
参考教程：[教程](https://denekow.github.io/2022/02608dd537.html)

1. 导入相关函数库
 ```
from astropy.io import fits # 从astropy的io模块倒入fits函数`\
import matplotlib.pyplot as plt #导入matplotlib的pyplot函数并重命名为plt`
```
2. 读取fits文件
```
file_path = '' #fits文件路径
file_name= ‘’ #fits文件名
gaia_data = fits.open() #读取fits文件`
```

3. 查看文件中的参数以及参数名
```note
fits文件结构的查询可以参考相关教程，[教程](https://denekow.github.io/2022/02608dd537.html)
```
```
gaia_data[1].header
```
