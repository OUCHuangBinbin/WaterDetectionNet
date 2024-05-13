# WaterDetectionNet
WaterDetectionNet: A New Deep Learning Method for Flood  Mapping with SAR Image Convolutional Neural Network
本研究系统配置如下：
scipy==1.2.1
numpy==1.17.0
matplotlib==3.1.2
opencv_python==4.1.2.30
torch==1.2.0
torchvision==0.4.0
tqdm==4.60.0
Pillow==8.2.0
h5py==2.10.0

使用方法：
打开train.py文件，设置好路径和数据集大小，即可跑模型
模型参数将保存在logs文件中，在多次迭代中会生成一个best_epoch_weights.pth文件，即最优参数。

预测模型：
打开sar_predict.py，设置好需要预测的SAR图像大小和所选模型，同时设置好相应路径即可完成。

Usage: 
open the train.py file, set the path and dataset size, you can run the model model parameters will be saved in the logs file, in many iterations will generate a best_epoch_weights.pth file, that is, the optimal parameters. 

Predictive model: 
open sar_predict.py, set the size of the SAR image to be predicted and the selected model, and also set the corresponding path to complete.

by HuangBinbin，Ocean University of China，2023.09.28
