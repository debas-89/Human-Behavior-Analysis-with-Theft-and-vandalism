# Human-Behavior-Analysis-with-Theft-and-vandalism
This project focuses on **human behavior analysis** using **Computer Vision and Deep Learning**.   The main objective is to detect, recognize, and classify human activities such as **fighting, theft, vandalism, and normal behavior** in real-time surveillance scenarios.  



By combining **YOLOv8 for object detection** and **CNN + LSTM-based sequence modeling**, the system can capture both **spatial features (individual frames)** and **temporal features (across video sequences)** to identify suspicious or abnormal behaviors.  

---

## 🚀 Features
- 🔹 **Real-time detection** of people in surveillance footage using YOLOv8  
- 🔹 **Action recognition** for multiple behavior categories (Normal, Fighting, Theft, Vandalism)  
- 🔹 **CNN + LSTM pipeline** for spatiotemporal feature learning  
- 🔹 **Frame-level compliance analysis** with accuracy metrics  
- 🔹 Scalable to support more classes with additional datasets  

---

## 🛠️ Tech Stack
- **Programming Language**: Python  
- **Deep Learning Frameworks**: PyTorch, TensorFlow/Keras  
- **Models Used**: YOLOv8, EfficientNetB0 (for feature extraction), CNN, LSTM  
- **Additional Tools**: OpenCV, Numpy, Matplotlib  
- **Dataset Structure**:

- /dataset
- 
├── train

│ ├── fighting
│ ├── theft
│ ├── vandalism
│ └── normal
└── test

├── fighting
├── theft
├── vandalism
└── normal
