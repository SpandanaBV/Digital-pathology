🧬 Deep Learning for Digital Pathology

This repository provides a complete toolkit for virtual slide analysis, image classification, and semantic segmentation in digital pathology using Keras, TensorFlow, and optionally Caffe.
It includes utilities for image preprocessing, slide management, model training, and inference, along with demo scripts to help you get started.

🚀 Features

🔍 Whole Slide Image (WSI) Analysis using OpenSlide

🧠 Image Classification & Segmentation with Keras and TensorFlow

🧩 Custom Data Generator (ImageDataGeneratorEXT) for segmentation with real-time augmentation

⚙️ Threaded Queues for efficient data loading and reconstruction

🧰 Modular utility scripts for:

Slide operations (slide_utils.py)

Image preprocessing (image_utils.py)

Model inference using Keras/TensorFlow (tf_utils_queue.py)

Optional Caffe integration (caffe_utils_queue.py)

| Library            | Version |
| ------------------ | ------- |
| Python             | 2.7     |
| OpenCV             | 3.4     |
| NumPy              | 1.14    |
| TensorFlow         | 1.7     |
| Keras              | 2.1     |
| OpenSlide          | 1.1     |
| Caffe *(optional)* | 0.15    |
