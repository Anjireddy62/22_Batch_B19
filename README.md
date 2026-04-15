# 🚀 Enhanced Network Attack Detection Using TCN–BiLSTM–Transformer

## 📌 Overview
This project presents a hybrid deep learning model for **network intrusion detection** using a combination of:
- Temporal Convolutional Network (TCN)
- Bidirectional LSTM (BiLSTM)
- Transformer Encoder

The model is designed to capture:
- Short-term patterns (TCN)
- Long-term dependencies (BiLSTM)
- Global relationships (Transformer)

It significantly improves detection accuracy for both common and rare cyberattacks.

---

## 🎯 Objectives
- Develop an intelligent intrusion detection system
- Handle imbalanced datasets using SMOTE
- Improve detection of low-frequency attacks
- Achieve high accuracy, precision, and F1-score

---

## 📊 Datasets Used
- NSL-KDD
- UNSW-NB15

---

## ⚙️ Technologies & Tools
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib

---

## 🧠 Model Architecture
The proposed model includes:
1. Feature Extraction Layer
2. TCN for local temporal features
3. BiLSTM for sequential learning
4. Transformer Encoder for global attention
5. Fully Connected Layer for classification

---

## 🔄 Data Preprocessing
- Handling missing values
- Min-Max normalization
- One-hot encoding
- Feature selection (BRFE)
- Sliding window segmentation
- SMOTE for class balancing

---

## 🏋️ Training Details
- Optimizer: Adam
- Learning Rate: 0.001
- Techniques Used:
  - Dropout
  - Early Stopping
  - Validation Monitoring

---

## 📈 Performance Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Results
| Model              | Accuracy |
|-------------------|---------|
| Random Forest     | 87.2%   |
| CNN               | 95.8%   |
| CNN-LSTM          | 96.4%   |
| CNN-BiLSTM        | 96.8%   |
| **Proposed Model**| **98.6%** |

---

## 🚀 Features
- Hybrid deep learning architecture
- Handles class imbalance effectively
- High detection accuracy
- Suitable for real-time intrusion detection

---

## 🔮 Future Work
- Multi-class attack classification
- Edge device deployment
- Federated learning for privacy
- Real-time IDS integration

---

## 👥 Team
- **Team Leader:** Anji Reddy Duggempudi  
- Vijay Kumar Naguru  
- Sri Saran Dasari  
- Karthik Mekala  
- Chalapathi Rao Tippana  
- Rajasekhar N  

---

## 📜 License
This project is for academic and research purposes only.

---

## 🙌 Acknowledgment
We thank our institution and mentors for supporting this project.

---

## 📬 Contact
For any queries:
📧 anjireddyduggempudi@gmail.com
