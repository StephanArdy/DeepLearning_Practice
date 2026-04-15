# Introduction
This is a deep learning object detection project to detect faces in images and videos. Built with Keras.

For labeling process, I used labelMe on my local machine by running `pip install labelme`.

For building the model, separate data manually to 3 folders: train, val, test with prefered ratio.

For training create folders:

```text
aug_data/
├── train/
│   ├── images/
│   └── labels/
├── val/
│   ├── images/
│   └── labels/
└── test/
	├── images/
	└── labels/
```

## What this project does:
1. Collecting and Annotating Images
2. Applying Bounding Box Augmentation
3. Build A Deep Object Detection Model
4. Evaluatiing Model Performance
5. Detect Faces In Real Time