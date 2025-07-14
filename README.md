# balloon-dataset

A collection of comics for training a balloon detection model

Trained models using YOLOv8:

* Chinese webtoon model trained on SQ: [download link](https://github.com/xulihang/balloon-dataset/releases/download/models/chinese_webtoon.zip)
* Korean webtoon model: [download link](https://github.com/xulihang/balloon-dataset/releases/download/models/korean_webtoon.zip)
* Model trained on 8k Manga, Webtoon, Manhua and Western Comic style Images by [comic-translate](https://github.com/ogkalu2/comic-translate): [download link](https://github.com/xulihang/balloon-dataset/releases/download/models/comic-speech-bubble.zip)
* [Japanese Artist CG model](https://github.com/xulihang/ImageTrans-docs/issues/711)

Trained models using Scaled YOLOv4:

* [Japanese manga model](https://github.com/xulihang/ImageTrans-docs/issues/135)
* Comics model trained on eBDtheque: [download link](https://github.com/xulihang/ObjectDetector/releases/download/models/yolo_darknet.zip)

## Use the Models in ImageTrans

1. Put the model files in ImageTrans's folder or the project folder.
2. Enable offline balloon detection in Preferences.
3. Use the balloon detection operation in ImageTrans to detect balloons.

You can also make a folder under `models` under ImageTrans's root and put the model files in it. Then, you can select which model to use in the project settings.

PS: if you have the model in `.pt` format and would like to use GPU, you can use this server to run the inference: https://github.com/xulihang/YOLO-Server

## Blog

[How to Train a YOLOv8 Object Detection Model](https://www.basiccat.org/how-to-train-yolov8-object-detection-model/)
