# Class01-01
介绍使用的软件环境及其安装方式

## 01-操作系统
Windows，Linux，macOS都可以
## 02-anaconda
我们使用anaconda软件管理Python包, 它不仅可以很方便的切换不同的Python环境，快捷安装Python依赖包，而且还附带了像JupyterLab, Qt Console和Spyder软件，这些IDE软件可以很方便的辅助我们编写Python代码。

推荐使用 Python 3.7的anaconda

anaconda的下载地址:https://www.anaconda.com

## 03-TensorFlow， Numpy， matplotlib
### a. TensorFlow安装
#### 首先，更新conda
```console
conda update conda
```
#### 添加 anaconda channel
```console
conda config --add channels anaconda
```
#### 安装TensorFlow
如果你的电脑上没有Nvidia的显卡，就安装CPU版本的TensorFlow，命令如下：
```console
conda install tensorflow
```
如果你的电脑上有Nvidia的显卡，可以安装GPU版本的TensorFlow，命令如下：
```console
conda install tensorflow-gpu
```
## 04-参考
Anaconda介绍、安装及使用教程: https://zhuanlan.zhihu.com/p/32925500
