# Problem Statements Overview

This directory contains three flagship AI/ML project tracks of increasing difficulty. Each subfolder holds a self-contained project with its own README, starter code, and detailed instructions.

## 📂 Directory Structure

## 📂 Directory Structure

```text
problems/
├── easy/
│   └── power-forecast/
│       └── README.md
├── medium/
│   └── tweet-dashboard/
│       └── README.md
└── hard/
    └── face-mask-detector/
        └── README.md
```

---

## 🚦 Tier 1 – Easy  
### Short-Term Power Demand Forecasting  
**Path:** `problems/easy/power-forecast/README.md`  
**Description:** Build and compare ARIMA, Random Forest, and LSTM models to forecast the next 24 hours of electricity demand.  
**Key Technologies:**  
- Data processing: Pandas, NumPy  
- Modeling: statsmodels (ARIMA), scikit-learn, TensorFlow/Keras (LSTM)  
- Visualization: Matplotlib, Plotly, Streamlit  
- Deployment: Docker, AWS Lambda, S3  

---

## 🚧 Tier 2 – Medium  
### Tweet Sentiment Dashboard  
**Path:** `problems/medium/tweet-dashboard/README.md`  
**Description:** Stream live tweets, train a TF–IDF/Word2Vec sentiment classifier, and display real-time sentiment charts in a React frontend.  
**Key Technologies:**  
- Data ingestion: Tweepy, GCP Pub/Sub  
- Modeling: scikit-learn, Gensim  
- Backend: Flask containerized on GCP Cloud Run, Firestore cache  
- Frontend: React.js, Chart.js (WebSockets)  
- Deployment: Docker, Kubernetes / Cloud Run  

---

## 🧩 Tier 3 – Hard  
### Face Mask Detector with Real-Time UI  
**Path:** `problems/hard/face-mask-detector/README.md`  
**Description:** Fine-tune a MobileNetV2 for mask detection, export to ONNX, build an autoscaling inference service, and display live video overlays.  
**Key Technologies:**  
- Deep Learning: TensorFlow/Keras, OpenCV, ONNX  
- Inference API: FastAPI, Docker, Azure Functions, AKS  
- MLOps: Terraform, Azure ML Pipelines, Azure Cosmos DB  
- Visualization: React + WebRTC video stream, Grafana metrics dashboard  

---

## 📝 Next Steps

1. **Enter a Tier Folder**  
   ```bash
   cd problems/easy/power-forecast