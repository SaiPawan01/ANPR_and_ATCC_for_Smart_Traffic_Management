# ANPR and ATCC for Smart Traffic Management

## 🚗 Project Overview

This project aims to develop an **Automatic Number Plate Recognition (ANPR)** and **Automatic Traffic Counting and Classification (ATCC)** system for smart traffic management. Additionally, it incorporates **Helmet Detection, Triple Riding Detection, and Accident Detection** using computer vision and deep learning techniques.
## 📌 Features

- **License Plate Detection & Recognition**: Extracts vehicle number plates and reads characters using OCR.
- **Vehicle Counting**: Counts vehicles passing through a designated area in real-time.
- **Traffic Classification**: Categorizes vehicles into different types (e.g., cars, trucks, motorcycles).
- **Real-time Processing**: Supports real-time video streams from cameras.
- **Helmet Detection**: Detects whether a motorcycle rider is wearing a helmet.
- **Triple Riding Detection**: Identifies if more than two persons are riding a motorcycle.
- **Accident Detection**: Detects accidents based on abrupt vehicle movements or falls.

## 🏗 Tech Stack

- **Programming Language**: Python
- **Object Detection Model**: YOLO (You Only Look Once) / SSD
- **Libraries & Frameworks:** OpenCV, TensorFlow
- **OCR Engine**: easyocr
- **Computer Vision**: OpenCV

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/SaiPawan01/ANPR_and_ATCC_for_Smart_Traffic_Management.git
cd ANPR_and_ATCC_for_Smart_Traffic_Management

# Install dependencies
pip install -r requirements.txt
```

### Running the Application

```bash
python app.py
```

## 📜 License

This project is licensed under the MIT License.

---
