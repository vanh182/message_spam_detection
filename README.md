# 📩 Spam Message Classification System

> An end-to-end Machine Learning project for SMS spam detection using multiple supervised learning algorithms and Apache Kafka for real-time message streaming.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange?logo=scikitlearn)
![Apache Kafka](https://img.shields.io/badge/Apache-Kafka-black?logo=apachekafka)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-success)
![LightGBM](https://img.shields.io/badge/LightGBM-ML-green)

---

# 📖 Overview

Spam Message Classification System is an end-to-end Machine Learning project designed to automatically classify SMS messages as **Spam** or **Ham (Non-Spam)**.

The project covers the complete machine learning pipeline, including text preprocessing, TF-IDF feature extraction, model training, evaluation, and Apache Kafka integration for real-time message streaming.

---

# ✨ Features

* 📩 SMS Spam Classification
* 🧹 Text Preprocessing
* 🔤 TF-IDF Feature Extraction
* 🤖 Multiple Supervised Machine Learning Models
* 📊 Model Performance Evaluation
* 📡 Apache Kafka Streaming Integration
* ☁️ Word Cloud Visualization

---

# 🛠 Tech Stack

| Category             | Technologies                                                                                      |
| -------------------- | ------------------------------------------------------------------------------------------------- |
| Programming Language | Python                                                                                            |
| Machine Learning     | Scikit-learn                                                                                      |
| Data Processing      | Pandas, NumPy                                                                                     |
| Feature Engineering  | TF-IDF                                                                                            |
| Streaming            | Apache Kafka                                                                                      |
| Models               | Logistic Regression, Complement Naive Bayes, Decision Tree, Random Forest, SVC, XGBoost, LightGBM |

---

# 🏗 Architecture

```text
Dataset
     │
     ▼
Data Cleaning
     │
     ▼
Text Preprocessing
     │
     ▼
TF-IDF Feature Extraction
     │
     ▼
Model Training
     │
     ▼
Performance Evaluation
     │
     ▼
Spam Prediction
```

### Real-time Prediction Pipeline

```text
SMS Message
     │
     ▼
Kafka Producer
     │
     ▼
Apache Kafka
     │
     ▼
Kafka Consumer
     │
     ▼
Trained ML Model
     │
     ▼
Spam / Ham Prediction
```

---

# 📂 Project Structure

```text
project
├── data
├── notebooks
├── models
├── kafka
├── images
├── src
│   ├── preprocessing
│   ├── training
│   ├── evaluation
│   └── prediction
├── requirements.txt
└── README.md
```

> *Adjust the structure above if it differs from your actual project.*

---

# 📸 Screenshots

## Dataset Sample

<p align="center">
<img src="./images/dataset.jpg" width="80%">
</p>

## Model Performance Comparison

<p align="center">
<img src="./images/model_comparison_table.png" width="80%">
</p>

The project evaluates seven supervised learning algorithms using Accuracy, Precision, Recall, and F1-score. Logistic Regression achieved the best overall performance with an accuracy of **98.47%**.

## Performance Visualization

<p align="center">
<img src="./images/model_comparison_chart.png" width="80%">
</p>

## Spam Word Cloud

<p align="center">
<img src="./images/spam_wordcloud.png" width="70%">
</p>

The Word Cloud highlights frequently occurring terms in spam messages, providing an intuitive visualization of common spam patterns.

---

# 🚀 How to Run

## Prerequisites

* Python 3.x
* pip
* Apache Kafka (optional for streaming)

## Clone the repository

```bash
git clone https://github.com/your-username/spam-message-classification.git
cd spam-message-classification
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Train the model

```bash
python train.py
```

## Run prediction

```bash
python predict.py
```

## Run Kafka Streaming (Optional)

Start Kafka and execute the producer and consumer applications:

```bash
python producer.py
python consumer.py
```

---

# 🚀 Future Improvements

* Deploy the trained model as a REST API
* Dockerize the application
* Apply Deep Learning models such as LSTM and BERT
* Deploy on cloud platforms
* Build a web-based interface for real-time spam detection

---

# 📄 License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute this project for educational and personal purposes.
