# Aegis-realtime-fraud-detection
An enterprise-level ML system for real-time financial fraud detection using stream ingestion, anomaly detection models, and live alerting.
# Aegis: Real-time Transaction Fraud Detection

Aegis is an enterprise-level Data Science and Machine Learning project designed to combat financial fraud by detecting and blocking fraudulent transactions in real-time. This system overcomes the latency limitations of traditional batch-based detection.

## 🚀 Project Overview
The system processes live transaction streams, scores them using advanced anomaly detection models, and triggers immediate actions (blocking and alerting) for high-risk activities.

### Key Features
- **Real-time Ingestion:** Scalable data streaming using Kafka/AWS Kinesis.
- **Anomaly Detection:** Implementation of Isolation Forest and Autoencoder models.
- **Microservice Architecture:** Model serving via FastAPI/Flask.
- **Live Monitoring:** Real-time visualization dashboard using Streamlit.

## 🏗️ Architecture & Modules
- **Data Stream Ingestion:** Handles high-velocity transaction data.
- **Feature Engineering Service:** Converts raw streams into model-ready features.
- **Model Deployment API:** Serves predictions with sub-second latency.
- **Online Learning:** Pipeline for continuous model retraining.


## 📅 Development Roadmap
| Phase | Backend (Data Pipeline & API) | Model Development (Scikit-learn/Keras) |
| :--- | :--- | :--- |
| **Week 1** | Setup Kafka mock stream & schema definition. | Train baseline Isolation Forest & SVM models. |
| **Week 2** | Build FastAPI model server & streaming logic. | Develop Deep Learning Autoencoder for anomalies. |
| **Week 3** | Build Kafka consumer & result storage service. | Fine-tune thresholds (Precision/Recall balance). |
| **Week 4** | Performance testing & Streamlit dashboard. | Final documentation & API stress testing. |

## 🛠️ Tech Stack
- **Languages:** Python
- **ML Frameworks:** Scikit-learn, TensorFlow/Keras
- **Streaming:** Apache Kafka / AWS Kinesis
- **API:** FastAPI
- **Dashboard:** Streamlit
-
