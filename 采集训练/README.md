# 两种采集人脸数据的方式

### 一种为：手动采集
将人脸放到指定方框中并按下空格键采集数据
不足之处：采集速度慢，要手动按
优点：只采集指定位置的人脸，防止其他人的干扰

### 另一种为：自动采集
利用opencv人脸分类模型自动检测人脸并直接保存数据

不足之处：若是在人多的情况下容易采集到他人的人脸导致混淆
优点：采集速度快

**注意：采集时输入的人脸ID从0开始**


# 训练模型
采集到足够数据后可运行训练数据.py得到模型文件
