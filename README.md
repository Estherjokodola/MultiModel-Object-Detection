# MultiModel-Object-Detection

**MultiModel-Object-Detection** is a Python pipeline for annotating images, videos, and real-time webcam streams using TensorFlow object detection models (SSD, Faster R-CNN, RFCNN). It provides easy-to-use scripts for inference, visualization, and exporting annotated media, making it ideal for computer vision research and prototyping.

---

## Features

- Annotate **images** and **videos** with bounding boxes and labels  
- Real-time object detection via **webcam streams**  
- Supports multiple TensorFlow models (SSD, Faster R-CNN, RFCNN)  
- Modular detection wrapper for **easy model swapping and customization**  
- Sample images and videos included for testing  

---

## Dependencies

Install all required dependencies in a single command:

```bash
pip install tensorflow>=2.0 opencv-python numpy matplotlib pillow tqdm

