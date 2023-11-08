# ResNet
use a model named ResNet to predict the class of flowers
1、data_set文件夹为花数据集，分为train、vel、pred,这三个文件夹分别作为训练集、验证集、测试集
2、split_data.py文件是对原始数据集进行分割，分为训练集、验证集、测试集
3、model.py是ResNet的模型架构
4、train.py是使用训练集对模型进行训练
5、predict.py是对单张花图片进行预测
6、batch_predict.py是对测试集图片进行预测
7、resNet34-pre.pth是从网上下载的ResNet的预训练模型
