# 2022winterHoliday
2022寒假目标检测器实践

# 目标检测器复现记录

[TOC]



## 1 YOLOv3 :star::star::star::star:

### 📖 参考

🔗 [[1804.02767\] YOLOv3: An Incremental Improvement (arxiv.org)](https://arxiv.org/abs/1804.02767)

🔗 [GitHub - ultralytics/yolov3: YOLOv3 in PyTorch > ONNX > CoreML > TFLite](https://github.com/ultralytics/yolov3)

### 🛢️数据集

🔗 [COCO2014 | Kaggle](https://www.kaggle.com/nadaibrahim/coco2014)

### 📜 步骤

> ```shell
> # Step1 克隆代码
> $ git clone https://github.com/ultralytics/yolov3.git
> $ cd yolov3
> 
> # Step2 创建环境（python3.6已验证可行，下以3.9为例）
> $ conda create -n yolov3_py39 python=3.9
> $ conda activate yolov3_py39
> $ pip install -r requirements.txt
> 
> # Step3 执行检测
> $ python detect.py --source ~/Datasets/COCO2014/val2014/val2014/
> ```

### 📝 结果

💻 GPU占用：1755MiB / 5926MiB

🚀 检测速度：约9600imgs / 10min

> Speed: 0.4ms pre-process, 36.0ms inference, 1.0ms NMS per image at shape (1, 3, 640, 640)

📁 检测结果：







## 2 YOLOv5 :star::star::star:

### 📜 步骤

> ```shell
> # Step1 克隆代码
> $ git clone https://github.com/ultralytics/yolov5.git
> $ cd yolov5
> 
> # Step2 创建环境（python3.6已验证可行，下以3.9为例）
> $ conda create -n yolov5_py39 python=3.9
> $ conda activate yolov5_py39
> $ pip install -r requirements.txt
> 
> # Step3 执行检测
> $ python detect.py --source ~/Datasets/COCO2014/val2014/val2014/
> ```

### 📝 结果

💻 GPU占用：1755MiB / 5926MiB

🚀 检测速度：约9600imgs / 10min

> Speed: 0.4ms pre-process, 36.0ms inference, 1.0ms NMS per image at shape (1, 3, 640, 640)

📁 检测结果：

| Input | Output |      |
| ----- | ------ | ---- |
|       |        |      |
|       |        |      |
|       |        |      |







## 3 FasterRCNN :star::star::star:





## 4 SSD :star::star::star:





## 5 RetinaNet :star:





## 6 CenterNet :star:



