# 🤖 Real-Time Industrial Object Detection, Tracking and Pose Estimation System

A comprehensive Computer Vision system designed for real-time industrial object perception and monitoring. The project combines deep learning–based object detection, multi-object tracking, pose estimation, model optimization, and web deployment to create a complete industrial vision pipeline suitable for automation and robotics applications.

The system leverages YOLOv8 for industrial object detection, ByteTrack for multi-object tracking, Kalman Filters for motion estimation, and OpenCV-based pose estimation techniques for object localization. The trained model was optimized using ONNX and deployed through a Streamlit-based web application for real-time inference and visualization.

---

## 🚀 Overview

Industrial environments require intelligent vision systems capable of detecting, tracking, and understanding object movement in real time. This project addresses that need by developing an end-to-end perception pipeline that can identify industrial objects, maintain object identities across frames, estimate object position and orientation, and provide deployment-ready inference performance.

The solution demonstrates how modern Computer Vision and AI techniques can be integrated into smart manufacturing, industrial automation, warehouse monitoring, and robotics applications.

---

## ✨ Key Features

- Real-time industrial object detection using YOLOv8
- Multi-object tracking with ByteTrack
- Kalman Filter-based motion prediction
- Pose estimation using OpenCV and solvePnP
- ONNX model optimization for efficient inference
- Browser-based deployment using Streamlit
- Real-time prediction and visualization interface
- End-to-end industrial perception pipeline

---

## 🛠️ Technology Stack

### Programming Language
- Python

### Deep Learning & Computer Vision
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy
- Pillow (PIL)

### Tracking & Localization
- ByteTrack
- Kalman Filter
- ArUco Marker Detection
- solvePnP

### Model Optimization
- ONNX
- ONNX Runtime

### Deployment
- Streamlit
- Google Colab

---

## 📂 Project Components

### 1. Industrial Object Detection
Trained a custom YOLOv8 model on an industrial object dataset to detect multiple object categories in real time.

### 2. Multi-Object Tracking
Implemented ByteTrack to maintain object identities across frames and support continuous object monitoring.

### 3. Motion Estimation
Integrated Kalman Filter-based tracking for robust object state prediction and smoother tracking performance.

### 4. Pose Estimation
Developed an OpenCV-based pose estimation module using ArUco markers and solvePnP for object localization.

### 5. Model Optimization
Converted the trained model into ONNX format to enable lightweight and deployment-ready inference.

### 6. Deployment
Built a Streamlit application that allows users to upload images and perform real-time industrial object detection directly from a web interface.

---

## 🎯 Industrial Applications

- Smart Manufacturing
- Industrial Automation
- Robotics Vision Systems
- Warehouse Monitoring
- Automated Inspection Systems
- Industrial Asset Tracking
- Real-Time Factory Analytics
- AI-Assisted Operational Monitoring

---

## 🏆 Key Achievements

- Developed an end-to-end industrial computer vision pipeline.
- Achieved real-time inference performance of approximately 38 FPS.
- Implemented object detection, tracking, motion estimation, and pose estimation within a single system.
- Optimized the trained model using ONNX for deployment-ready performance.
- Built a complete browser-based application for industrial vision inference.

---

## 🔮 Future Enhancements

- Real-time video stream processing
- Advanced deep-learning-based 6D pose estimation
- Edge deployment using OpenVINO and TensorRT
- Industrial anomaly detection
- Predictive maintenance integration
- Expanded industrial object categories

---

## 📌 Conclusion

This project demonstrates a complete industrial perception system capable of detecting, tracking, and localizing industrial objects in real time. By integrating object detection, tracking, pose estimation, optimization, and deployment into a unified pipeline, the solution showcases practical applications of Computer Vision and AI in industrial automation and robotics environments.
