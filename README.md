# Face Recognition using OpenCV & Python

## 📌 Project Overview
This project implements **face recognition** using **OpenCV** and **Python**. It allows users to detect and recognize faces from images and videos using a pre-trained model.

## 🚀 Features
- Detects and recognizes faces in real-time
- Uses OpenCV for face detection
- Stores and matches faces from a database
- Supports both image and video-based recognition

## 🛠️ Installation
### **Prerequisites**
Ensure you have **Python 3.x** installed. Then, install the required dependencies:

```bash
pip install opencv-python numpy dlib face-recognition
```

### **Clone the Repository**
```bash
git clone https://github.com/yourusername/face_recognition.git
cd face_recognition
```

## 📂 Project Structure
```
face_recognition_project/
│── Create_Database_test.py   # Script to create a database of faces
│── face_identification.py    # Main script for face recognition
│── face_rec.py               # Face detection and recognition script
│── README.md                 # Project documentation
│── .gitignore                # Git ignore file
```

## 📸 Usage
### **1. Creating a Face Database**
Run the following command to capture and store face images in the database:
```bash
python Create_Database_test.py
```

### **2. Face Recognition**
To recognize faces from a video stream:
```bash
python face_identification.py
```

To recognize faces from an image:
```bash
python face_rec.py --image path/to/image.jpg
```

## 🎯 Future Improvements
- Improve accuracy using deep learning models (e.g., CNN, ResNet)
- Implement a GUI for user-friendly interaction
- Optimize face recognition speed for large datasets

## 📜 License
This project is open-source and available under the **MIT License**.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📧 Contact
For questions or suggestions, reach out to **[Your Name](mailto:emsambit@gmail.com)**.

---
⭐ **If you find this project useful, give it a star!** ⭐

