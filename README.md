# 🖐️ Sign Language Interpreter  

A deep learning-based project that interprets **American Sign Language (ASL)** hand gestures using **Convolutional Neural Networks (CNNs)**.  
The system captures hand signs through a webcam and predicts the corresponding alphabet in real time.  

---

## 📌 Features
- Real-time **sign detection** using OpenCV & CNN.  
- Trained on **custom ASL dataset**.  
- Model built with **TensorFlow/Keras**.  
- Includes data collection, preprocessing, training, and testing scripts.  
- GUI-free and camera-based sign prediction.  

---

## 📂 Project Structure
Sign-Language-Interpreter/
│── src/
│ ├── train.py # Train CNN model
│ ├── test.py # Evaluate model
│ ├── cam_test.py # Real-time webcam detection
│ ├── final_pred.py # Final prediction script
│ ├── cnn_models.py # CNN architectures
│ ├── preprocess_image.py # Preprocessing pipeline
│ ├── data_collection_final.py # Collect training data
│ ├── create_csv.py # Generate CSV for dataset
│ ├── requirement.txt # Dependencies (rename to requirements.txt)
│ └── ...
│
├── Documentation/ # Research paper, report, results
│ ├── Conference paper.pdf
│ ├── Final Report on ASL.pdf
│ ├── Confusion matrix.png
│ ├── Model Accuracy.png
│ └── images/ (sample signs)
│
├── models/
│ └── cnn8grps_rad1_model.h5 # Pre-trained model
│
├── README.md
