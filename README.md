# model

视频数据集
https://pan.baidu.com/s/1O6bdhyKXIhJasvDc5aPtMQ?pwd=7g2m

图片数据集
通过网盘分享的文件：1s1fps.zip
链接: https://pan.baidu.com/s/1orFBSyna0jOi20KjShouag?pwd=dtn7 提取码: dtn7

目标检测
先看官方文档，读懂参数

PaddlePaddle/PaddleYOLO: 🚀🚀🚀 YOLO series of PaddlePaddle implementation, PP-YOLOE+, RT-DETR, YOLOv5, YOLOv6, YOLOv7, YOLOv8, YOLOv10, YOLO11, YOLOX, YOLOv5u, YOLOv7u, YOLOv6Lite, RTMDet and so on. 🚀🚀🚀 (github.com)


文档教程
入门教程
•	安装说明
•	快速体验
•	数据准备
•	PaddleDetection全流程使用
•	FAQ/常见问题汇总
进阶教程
•	参数配置
o	PP-YOLO参数说明
•	模型压缩(基于PaddleSlim)
o	剪裁/量化/蒸馏教程
•	推理部署
o	模型导出教程
o	Paddle Inference部署
	Python端推理部署
	C++端推理部署
o	Paddle-Lite部署
o	Paddle Serving部署
o	ONNX模型导出
o	推理benchmark
•	进阶开发
o	数据处理模块
o	新增检测模型
o	二次开发教程
	目标检测

找个开源的看看，大致了解。这里面有EazyData的标注教程，也可以用labelme进行标注
【X-SmartCar】人工智能模型组Baseline之目标检测模型训练与导出 - 飞桨AI Studio星河社区 (baidu.com)
Labelme安装及使用教程-CSDN博客

B站也有很多视频
【在Anaconda虚拟环境中安装labelme库】https://www.bilibili.com/video/BV1qp4y1475o?vd_source=99806b0a9731b078e842a8841f215117


语义分割
同理，依旧看官方文档
PaddlePaddle/PaddleSeg: Easy-to-use image segmentation library with awesome pre-trained model zoo, supporting wide-range of practical tasks in Semantic Segmentation, Interactive Segmentation, Panoptic Segmentation, Image Matting, 3D Segmentation, etc. (github.com)
选开源项目进行操作
•	使用PP-HumanSegV2进行人像分割
•	使用PP-HumanSegV1进行人像分割
•	使用PP-LiteSeg进行遥感道路分割
•	PaddleSeg实战之人脸部件分割与变妆
•	PaddleSeg实战之小数据集3D椎骨分割
•	PaddleSeg实战之车道线图像分割
•	PaddleSeg动态图API使用教程
•	10分钟上手PaddleSeg
•	车路协同：交互式分割技术在智慧建图中的应用和实践
•	基于PaddleSeg的美甲预览机
•	基于PaddleSeg的钢筋长度超限监控


做分割数据集的时候可能会遇到格式问题，需要写代码进行转化。
json转mask-CSDN博客
【json转白色mask】_json转mask-CSDN博客

ONNX转RKNN及RKNN推理部署
doc文件夹内有快速入门教程，手中无开发板者，仅看如何配置rknn_toolkit2环境以及模型转化部分即可。
在Windows上面转化rknn模型需要先安装虚拟机（推荐WSL2，Ubuntu版本号为22.04）或者下载docker拉取镜像。
rknn-toolkit2/rknn-toolkit2 at master · airockchip/rknn-toolkit2 (github.com)
 
examples文件夹内，cpp文件夹为C++对应推理文件。Python文件夹内convert.py为转化代码。Onnx转rknn需要特定环境rknn_toolkit2。
airockchip/rknn_model_zoo (github.com)
 

