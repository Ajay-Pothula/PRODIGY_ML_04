# 🖐️ Hand Gesture Recognition using CNN

This project implements a **Convolutional Neural Network (CNN)** to classify **hand gestures** from the LeapGestRecog dataset.  
The model can identify **10 different gestures** and can be extended for gesture-based control systems or Human-Computer Interaction (HCI).

---

## 📌 Project Overview
- Loads and preprocesses the **hand gesture dataset**.
- Performs **data augmentation** to make the model more robust.
- Trains a **CNN model** using TensorFlow/Keras.
- Evaluates the model with accuracy, loss, confusion matrix, and classification report.
- Visualizes random predictions and training performance.

---

## 📂 Dataset
We used the **[LeapGestRecog dataset](https://www.kaggle.com/gti-upm/leapgestrecog)**, which contains **20,000+ images** of 10 gesture classes:

1. Palm  
2. L  
3. Fist  
4. Fist Moved  
5. Thumb  
6. Index  
7. OK  
8. Palm Moved  
9. C  
10. Down  

Each class has **2000 grayscale images (320x240)**.
