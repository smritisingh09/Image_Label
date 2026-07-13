# Image_Label

# 🌸 Flower Image Annotation Tool

## 📌 Project Overview
The Flower Image Annotation Tool is a computer vision project developed to create annotated datasets for flower images. The project allows users to draw bounding boxes around flowers and generate annotations in YOLO format, which can be used to train object detection models.

---

## 🎯 Objectives
- Annotate flower images using bounding boxes.
- Generate YOLO-compatible label files.
- Prepare a dataset for object detection and machine learning tasks.
- Learn the fundamentals of image annotation and dataset preparation.

---

## 🗂️ Project Structure

```text
Image_Label/
│
├── dataset/
│   └── images/
│       ├── image1.jpg
│       ├── image2.jpg
│       └── ...
│
├── obj_train_data/
│   ├── image1.jpg
│   ├── image1.txt
│   ├── image2.jpg
│   ├── image2.txt
│   └── ...
│
├── annotation_tool.ipynb
├── annotate.ipynb
├── obj.data
├── obj.names
├── train.txt
└── README.md
```

---

## 🌼 Dataset
The dataset contains images of various flower species, including:

- Arabian Jasmine (Mogra)
- Indian Mustard
- Sadaabahar
- Cornflower
- Coriander
- Delphiniums
- Garland Daisy
- Lily
- Poppy
- Plumeria
- Bougainvillea
- Petunias
- Water Lily
- Yellow Cosmos
- And many more flower species.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Jupyter Notebook
- CVAT (Computer Vision Annotation Tool)
- YOLO Annotation Format
- Visual Studio Code (VS Code)

---

## 🏷️ Annotation Format

Each image has a corresponding `.txt` file in YOLO format:

```text
<class_id> <x_center> <y_center> <width> <height>
```

Example:

```text
0 0.512500 0.481250 0.325000 0.450000
```

Where:

- `class_id` → Object class number
- `x_center` → X-coordinate of bounding box center
- `y_center` → Y-coordinate of bounding box center
- `width` → Width of bounding box
- `height` → Height of bounding box

All coordinates are normalized between 0 and 1.

---

## 🚀 Features

- Manual image annotation using bounding boxes.
- Generation of YOLO annotation files.
- Easy dataset preparation for object detection.
- Supports multiple flower images.
- Compatible with YOLO-based object detection models.

---

## 📚 Applications

- Flower Detection
- Object Detection
- Computer Vision Research
- Machine Learning and Deep Learning Projects
- Educational and Academic Projects

---

## 👩‍💻 Author

**Smriti Singh**  
B.Tech in Information Technology  
Institute of Engineering and Technology (IET)  
Deen Dayal Upadhyay Gorakhpur University, Gorakhpur

---