1、下载代码 链接：https://github.com/zaiwuwu/yolov5-pyqt5 或者打开终端直接 git clone https://github.com/zaiwuwu/yolov5-pyqt5.git 

2、构建环境 `注意关闭代理否则会出现超时的情况`


（1）创建虚拟环境 conda create -n yolov5-pyqt5 ![image](https://github.com/zaiwuwu/yolov5-pyqt5/assets/156164792/99e3179e-9bdd-47f0-8515-957d86b7d330)



（2）激活虚拟环境 conda activate yolov5-pyqt5 ![image](https://github.com/zaiwuwu/yolov5-pyqt5/assets/156164792/a7863cf6-4d5f-43f0-9f8a-02e6fd6f0169)


（3）cd进入下载代码文件中requirements.txt所在目录安装依赖 pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple `如果部分依赖安装不上请点击 https://blog.csdn.net/weixin_45687036/article/details/123376144 换源` ![image](https://github.com/zaiwuwu/yolov5-pyqt5/assets/156164792/9461f99d-e571-40f4-95cf-0db37154728f) 
3、运行程序 

（1）打开pycharm添加刚刚创建的解释器![image](https://github.com/zaiwuwu/yolov5-pyqt5/assets/156164792/dab596d5-63dd-4804-857f-cae7679e687a) 
（2）运行main_logic.py`账号密码都是admin` 

（3）加载已经训练好的权重文件并初始化模型![image](https://github.com/zaiwuwu/yolov5-pyqt5/assets/156164792/1645c132-e8ef-4351-828a-9d79d2c247e3) 

（4）图片检测![image](https://github.com/zaiwuwu/yolov5-pyqt5/assets/156164792/b8937301-64fa-406b-89e2-847eb16d888c) 

（5）视频检测![image](https://github.com/zaiwuwu/yolov5-pyqt5/assets/156164792/3a0f5468-40b6-402b-a9c8-53e870b85259)  

（6）摄像头检测不进行演示 



运行出现问题可能是因为我采用GPU运行的原因 如果你的电脑不支持cuda和cudnn 请打开detect_logic.py的71行将default='0'修改为default=''![image](https://github.com/zaiwuwu/yolov5-pyqt5/assets/156164792/ea741f9a-dcb5-4584-ba19-0d8afb0d76ab) 


如果你想使用GPU运行yolo可以自行百度下载cuda和cudnn并下载适配cuda的torch、torchvison、torchaudio 
我的联系方式：zhaoyiyong2021@163.com











