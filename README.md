# Hand Gesture Recognition using SVM

## 🚀 Overview
This project is a **real-time hand gesture recognition system** using **Support Vector Machine (SVM)** and **OpenCV**. It detects hand gestures from images or live video, enabling intuitive **human-computer interaction** and gesture-based control systems.

## 📌 Features
✅ Real-time gesture recognition using a webcam 📷  
✅ Uses **SVM classifier** with **HOG features**  
✅ Supports multiple hand gestures ✋🤞👊  
✅ Works on **Python + OpenCV + Scikit-learn**  
✅ Easily extendable for new gestures 🚀  

## 🛠 Installation
### 1️⃣ Install Dependencies
```bash
pip install opencv-python numpy scikit-learn joblib
```

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/hand-gesture-recognition.git
cd hand-gesture-recognition
```

## 🎯 Dataset Preparation
1. **Download a Hand Gesture Dataset** (or use your own).
2. Organize images into folders (one per gesture class).
3. Extract features using **HOG (Histogram of Oriented Gradients)**.

## 🔍 Training the SVM Model
Run the training script:
```bash
python train_svm.py
```
This will:
✅ Extract features from images  
✅ Train an SVM classifier  
✅ Save the trained model (`gesture_svm_model.pkl`)  

## 📷 Running Real-Time Gesture Recognition
Run the real-time detection script:
```bash
python real_time_recognition.py
```
📌 **How to Use?**
1️⃣ Keep your hand inside the camera frame.  
2️⃣ The model predicts and displays the gesture name.  
3️⃣ Press **'q'** to exit.  

## 🚀 Future Improvements
🔹 Use **MediaPipe Hands** for better hand detection  
🔹 Train a **CNN model** for higher accuracy  
🔹 Add more **gesture classes**  
🔹 Integrate with **smart home or gaming apps**  

## 💡 Contributing
Feel free to **fork this repo** and add more gestures or improve the model. Pull requests are welcome! 😊

## 🔗 Contact
👨‍💻 **Muhammad ilyas**  
📧 ilyaslayyah786@gmail.com 
🔗 [GitHub Profile](https://github.com/ilyaslayyah123)  

