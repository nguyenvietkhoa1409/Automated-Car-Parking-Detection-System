# Automated Car Parking Detection System 🚗

Welcome to the **Automated Car Parking Detection System**, built by **nguyenvietkhoa1409**. This repository presents a complete, AI-powered solution for **detecting available parking spaces** in real-time using computer vision and deep learning:contentReference.

## 🙏 Acknowledgments

This project is inspired by and based on the work from [Chando0185/car_parking_detection_space_count](https://github.com/Chando0185/car_parking_detection_space_count).  
Special thanks to the original author for the clear approach to parking space detection.


---

## 🌟 What Is This Project About?

In many urban environments, drivers spend valuable time circling parking lots searching for an open space. This project leverages camera feeds and neural networks to automate that process.

- **Deep Learning + Computer Vision**: A custom-trained CNN model classifies each predefined parking slot as *occupied* or *vacant* using image frames.
- **Real-Time Performance**: The system can process live video streams for continuous monitoring of parking functionality.
- **Web Interface Support**: With Flask integration, users can view parking status updates in real time via a lightweight web page.

---


📁 Repository Structure
```bash
Automated-Car-Parking-Detection-System/
├── Car_parking_detection.ipynb # Interactive training and demo notebook
├── Trained model — [Download](https://drive.google.com/file/d/14C7PmeS7yfP987bdyF7ZHuybPUr5yF-3/view?usp=sharing)
├── data_collection.py # Code to capture and preprocess parking images
├── train_data.zip # Labeled training dataset (download separately)
├── car_test.zip # Test frames or image dataset (external source)
├── carposition.pkl # Pickled configuration of parking slot regions
├── requirements.txt # Dependencies 
├── main.py # Real-time detection pipeline code
├── test.py # Evaluation and visualization tools
└── README.md # Project documentation
```

