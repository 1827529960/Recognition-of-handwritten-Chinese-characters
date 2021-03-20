# 手写汉字的识别

#### 介绍
基于tensorflow的高阶api keras的手写汉字的识别

#### 软件架构
使用vggnet网络进行搭建


#### 安装教程

1.  安装anaconda，创建python=3.7的环境
2.  需要使用的库都在pagename.txt文件中，
请使用python -m pip install -r pagename.txt命令进行安装


#### 使用说明
代码来自https://github.com/yogurtcon/Handwritten-Chinese-character-recognition-system
不过此仓库没有具体信息，教程等
文字来源参考我另一个仓库https://gitee.com/Alabatens/casia-hwdb-decompression.git中的gnt2png.py


#### 程序说明
data文件夹下是需要训练的数据
后期需要识别的字放到original pic文件夹下，图片格式一定要用png，jpg无法识别
跑多少轮在fit.py内更改epochs值就行，我训练了40轮，精度是87%左右


