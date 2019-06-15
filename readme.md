Ubuntu16.04系统下，项目运行环境配置步骤：

1、有一台安装anaconda的电脑，进入终端，在anaconda中新建一个名字为bank-card-ocr的Python=3.6的环境。执行命令：conda create -n bank-card-ocr python=3.6 

2、在Bank-Card-Ocr目录下进入终端，执行 conda activate bank-card-ocr 激活刚刚创建的环境

3、执行 sh setup.sh 安装运行项目需要用到的库，或者打开 setup.sh文件,手动一行一行代码执行安装库。

4、然后执行 cd ctpn/lib/utils 执行 sh make.sh 完善运行环境
