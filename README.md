# OCR
>最近在做OCR的项目，以下是一些资料
## 目录 
###
* [最近的论文and代码(更新ing)](https://github.com/hwalsuklee/awesome-deep-text-detection-recognition)
### 调研
* [ocr调研报告](./Documents/基于深度学习的场景文本识别调研.pptx)
### 论文
* [1.ASTER_notes](./Documents/ASTER_notes.pptx)
  * [1.1.STN_notes](./Documents/STN_notes.pdf)
  * [1.2.TPS_notes](./Documents/TPS_notes.docx)
  * [1.3.Aster code](https://github.com/bgshih/aster)
### 数据集
* [1.中文数据集](https://pan.baidu.com/s/1QkI7kjah8SPHwOQ40rS1Pw)
  * 密码：lu7m
  * 共约364万张图片，按照99:1划分成训练集和验证集
  * 数据利用中文语料库（新闻 + 文言文），通过字体、大小、灰度、模糊、透视、拉伸等变化随机生成
  * 包含汉字、英文字母、数字和标点共5990个字符
  * 每个样本固定10个字符，字符随机截取自语料库中的句子
  * 图片分辨率统一为280x32
### 小tricks
* [1.图片数据增强包](https://github.com/albu/albumentations)
* [2.SynthText_Chinese_version(自然场景的文字生成)](https://github.com/JarveeLee/SynthText_Chinese_version)
* [3.印刷体文字生成](https://github.com/Belval/TextRecognitionDataGenerator)
* [4.印刷体文字生成之中文](https://github.com/Sanster/text_renderer)
