# ICDAR2PASCAL_VOC
Convert scene text dataset ICDAR2013, ICDAR2015 to PASCAL_VOC dataset

## 安装依赖包
```py
pip install -r requirements.txt
```

## ICDAR2013 dataset 转化为 PASCAL_VOC dataset 格式
下载 ICDAR2013 dataset 解压放入 ICDAR2013 文件夹，包含：
- Challenge2_Training_Task12_Images
- Challenge2_Training_Task1_GT
- Challenge2_Test_Task12_Images
- Challenge2_Test_Task1_GT
#### 执行
```py
python ICDAR2013/trans.py
```

## ICDAR2015 dataset 转化为 PASCAL_VOC dataset 格式
下载 ICDAR2015 dataset 解压放入 ICDAR2013 文件夹，包含：
- ch4_training_images
- ch4_training_localization_transcription_gt
- ch4_test_images
#### 执行
```py
python ICDAR2015/trans.py
```
