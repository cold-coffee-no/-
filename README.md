模型文件中的yolov3—fenlei.py文件用于将数据集中的图片按80%的比例进行分类，分为训练集和验证集，同时将XML格式的文件转化为yolo格式的
train.py文件用于训练，可以根据自己的需求修改训练轮次，一轮的训练个数。训练后的结果会在yolov3-9.5.0/runs/train/exp2中
同时新加了一个test.py文件用于测试数据集训练结果，训练后的结果会在yolov3-9.5.0/runs/test/exp中
detect.py文件用于对新图片进行标注，可将图片直接放在data文件夹目录下，标注后的图片会在yolov3-9.5.0/runs/detect/exp/1.jpg目录下
requirements.txt文本中是所依赖的包。
最好的权重文件“best.pt”在weights文件夹中可以找到。
