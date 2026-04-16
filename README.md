# Network Intrusion Detection Using Machine Learning Techniques

A machine learning-based **Network Intrusion Detection System (NIDS)** that classifies network traffic as **normal or malicious** using the **NSL-KDD dataset**. This project is built in **Google Colab / Jupyter Notebook using Python and Scikit-learn**.

---

## 🚀 Project Overview

The goal of this project is to detect suspicious network activity and cyberattacks by training ML models on network traffic features.

The model learns patterns from historical traffic data and predicts whether a connection is:

* ✅ Normal traffic
* 🚨 Intrusion / Attack traffic

This helps improve **network security monitoring**, **threat detection**, and **real-time anomaly detection systems**.

---

## 🎯 Objectives

* Build an ML-based NIDS
* Preprocess and clean NSL-KDD traffic data
* Encode categorical network features
* Train a high-accuracy classifier
* Evaluate intrusion detection performance
* Save trained model for deployment

---

## 🧠 Machine Learning Workflow

1. Dataset Collection
2. Data Preprocessing
3. Feature Encoding
4. Train-Test Split
5. Feature Scaling
6. Model Training
7. Prediction
8. Performance Evaluation
9. Model Saving

---

## 📂 Dataset

This project uses the **NSL-KDD dataset**, an improved version of KDD Cup 1999.

### Dataset File

* `KDDTrain+.txt`

### Features Include

* duration
* protocol_type
* service
* flag
* src_bytes
* dst_bytes
* count
* srv_count
* error rates
* host-based traffic features
* label

---

## 🛠️ Tech Stack

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Joblib**

---

## 📦 Installation

Install required dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

---

## ▶️ How to Run

### Google Colab

1. Open Google Colab
2. Upload `KDDTrain+.txt`
3. Run notebook cells step by step
4. Train model
5. Download `nids_model.pkl`

### Jupyter Notebook

```bash
jupyter notebook
```

Open:

* `NIDS_Project.ipynb`

---

## 🧪 Model Used

This project uses:

* **Random Forest Classifier**

Why?

* High accuracy
* Works well with mixed feature types
* Handles large datasets efficiently
* Great baseline for intrusion detection

---

## 📊 Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

Expected performance:

* ✅ **85%–95% accuracy** on NSL-KDD

---

## 💾 Model Saving

The trained model is saved as:

* `nids_model.pkl`

This can be later used in:

* Flask app
* Streamlit dashboard
* Real-time packet monitoring
* API deployment

---

## 📁 Project Structure

```text
NIDS_Project/
│
├── NIDS_Project.ipynb
└── README.md
```

---

## 🔮 Future Improvements

* Multi-class attack classification
* Real-time packet sniffing using Scapy
* CICIDS2017 dataset support
* Deep learning (LSTM / ANN)
* Streamlit dashboard
* Live alert system
* Explainable AI with SHAP

---

## 🌟 Use Cases

* Enterprise network monitoring
* SOC alert systems
* Malware traffic detection
* DDoS detection
* Research & academic projects
* Cybersecurity final year projects

---

## 👩‍💻 Author

**Kasturi Navya**

Machine Learning | Cybersecurity | AI Projects

---

## 📜 License

This project is for **academic and educational purposes**.
