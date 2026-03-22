# 🚦 Traffic Sign Image Classification

## 📌 Overview
This project focuses on classifying traffic sign images using **Deep Learning**, specifically **Convolutional Neural Networks (CNNs)**. It is an essential component in autonomous vehicle systems, helping vehicles understand and follow traffic rules in real time.

The model is trained on the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset and achieves high accuracy in recognizing different traffic signs.

---

## 🎯 Objectives
- Build a robust CNN model for traffic sign classification  
- Achieve high accuracy in multi-class image classification  
- Enable real-time applicability for autonomous driving systems  
- Improve road safety through AI-based recognition  

---

## 📂 Dataset
- **Dataset Used:** German Traffic Sign Recognition Benchmark (GTSRB)  
- **Total Images:** 50,000+  
- **Classes:** 43 traffic sign categories  
- **Train/Test Split:** ~80% training, 20% testing  

### 🔧 Preprocessing Steps:
- Image resizing to 30x30 pixels  
- Normalization (pixel values between 0 and 1)  
- Data augmentation (rotation, scaling, color adjustments)  

---

## 🧠 Model Architecture
The model uses a **Convolutional Neural Network (CNN)** with:

- Convolutional Layers (32 & 64 filters)
- Kernel sizes: 5x5 and 3x3  
- MaxPooling layers for dimensionality reduction  
- Dropout layers (0.25 & 0.5) to prevent overfitting  
- Fully Connected Dense Layer (256 neurons)  
- Output Layer with 43 classes (Softmax activation)  

### ⚙️ Training Details:
- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  
- Epochs: 15  
- Batch Size: 32  

---

## 📊 Results
- ✅ **Accuracy:** ~94% on test dataset  
- 📉 Stable training and validation loss  
- 📈 Strong generalization with minimal overfitting  

### Insights:
- Performs well on distinct signs (Stop, Speed Limit)  
- Slight confusion in visually similar signs  
- Dropout helped improve model performance  

---

## 📈 Exploratory Data Analysis (EDA)
- Accuracy increased significantly after early epochs  
- Loss decreased steadily, indicating good convergence  
- No major overfitting observed  

---

## 🚀 Applications
- Autonomous Vehicles (AVs)  
- Advanced Driver Assistance Systems (ADAS)  
- Smart Traffic Monitoring Systems  

---

## 🔮 Future Improvements
- Use Transfer Learning (ResNet, VGG)  
- Improve performance on similar-looking signs  
- Real-time video classification  
- Use GANs for synthetic data generation  

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  

---

## 👩‍💻 Authors
- **Khanak Gupta**  
- Nethi Nushitha Sri  

---

## 📚 References
- GTSRB Dataset  
- CNN Research Papers  
- Deep Learning for Computer Vision  

---

## 📌 Conclusion
This project demonstrates the effectiveness of CNNs in solving real-world problems like traffic sign recognition. With further improvements, such models can significantly enhance safety and efficiency in autonomous driving systems.

---
