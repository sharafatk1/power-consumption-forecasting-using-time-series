<div align="center">

# ⚡ Power Consumption Forecasting Using Time-Series Models

### AI-powered Hourly Electricity Load Forecasting using Deep Learning, Machine Learning & Hybrid Models

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)]()
[![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange?logo=tensorflow)]()
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)]()
[![XGBoost](https://img.shields.io/badge/XGBoost-GradientBoosting-green)]()
[![Pandas](https://img.shields.io/badge/Pandas-DataAnalysis-blue?logo=pandas)]()
[![NumPy](https://img.shields.io/badge/NumPy-ScientificComputing-blue?logo=numpy)]()

Predicting hourly electricity demand using Machine Learning, Deep Learning, and Hybrid Time-Series Forecasting Models on real-world NYISO electricity load data.

</div>

---

# 📌 Project Overview

Accurate electricity demand forecasting is essential for smart grids, energy management, and demand-response systems.

This project presents a comparative analysis of multiple forecasting models using hourly electricity consumption data obtained from the **New York Independent System Operator (NYISO)**.

Five forecasting models were developed and evaluated:

- 🔹 Long Short-Term Memory (LSTM)
- 🔹 Gated Recurrent Unit (GRU)
- 🔹 Random Forest
- 🔹 Gradient Boosting Machine (GBM)
- 🔹 Hybrid LSTM + GBM

The objective was to identify the model that provides the highest forecasting accuracy while maintaining strong generalization performance.

---

# 🚀 Features

✅ Real-world NYISO hourly electricity dataset

✅ Multi-year historical data (2021–2026)

✅ Complete preprocessing pipeline

✅ Feature Engineering

- Lag Features
- Rolling Statistics
- Calendar Features
- Time-based Features

✅ Deep Learning Models

- LSTM
- GRU

✅ Machine Learning Models

- Random Forest
- Gradient Boosting Machine (GBM)

✅ Hybrid Forecasting Architecture

LSTM + GBM

✅ Model Evaluation

- RMSE
- MAE
- MAPE
- R² Score

---

# 🏗 Project Architecture

```

NYISO Dataset
│
▼

Data Preprocessing

│

├── Missing Value Handling

├── Duplicate Removal

├── Outlier Detection

├── Feature Engineering

└── Data Normalization

│
▼

Model Training

│

├── GRU

├── LSTM

├── Random Forest

├── GBM

└── Hybrid LSTM + GBM

│
▼

Performance Evaluation

│

├── RMSE

├── MAE

├── MAPE

└── R² Score

```

---

# 📂 Repository Structure

```

Power-Consumption-Forecasting/

│

├── data/

│ ├── NYISO CSV Files

│ └── README.md

│

├── notebooks/

│ └── power_consumption_forecasting.ipynb

│

├── reports/

│ ├── Research_Paper.pdf

│ ├── Final_Report.pdf

│ └── Presentation.pptx

│

├── results/

│ ├── lstm_prediction.png

│ ├── gru_prediction.png

│ ├── gbm_prediction.png

│ ├── rf_prediction.png

│ └── hybrid_prediction.png

│

├── requirements.txt

└── README.md

```

---

# 📊 Dataset

**Source**

New York Independent System Operator (NYISO)

Dataset consists of:

- Hourly Electricity Load
- Multiple Load Zones
- Historical Grid Demand
- Multi-year Time-Series Data (2021–2026)

---

# ⚙ Data Preprocessing

The preprocessing pipeline includes:

- Missing Value Imputation
- Duplicate Timestamp Handling
- Rolling Z-Score Outlier Detection
- Datetime Conversion
- Feature Engineering
- Lag Feature Generation
- Rolling Mean & Standard Deviation
- Min-Max Scaling
- Chronological Train/Test Split

---

# 🤖 Models Implemented

| Model | Type |
|---------|------------|
| GRU | Deep Learning |
| LSTM | Deep Learning |
| Random Forest | Machine Learning |
| GBM | Gradient Boosting |
| Hybrid LSTM + GBM | Hybrid Model |

---

# 📈 Performance Comparison

| Model | RMSE | MAE | MAPE | R² |
|------|------|------|------|------|
| GRU | 87.98 | 63.85 | 1.1024 | 0.9941 |
| LSTM | 78.34 | 58.22 | 1.0264 | 0.9954 |
| Random Forest | 72.94 | 51.04 | 8.8658 | 0.9960 |
| GBM | 62.70 | 43.97 | 0.7506 | 0.9954 |
| ⭐ Hybrid LSTM + GBM | **52.50** | **35.43** | **0.6043** | **0.9979** |

---

# 🏆 Best Performing Model

🏅 **Hybrid LSTM + GBM**

Performance Highlights

- RMSE: **52.50 MW**
- MAE: **35.43 MW**
- MAPE: **0.6043%**
- R² Score: **0.9979**

The Hybrid model achieved the highest forecasting accuracy by combining the temporal learning capability of LSTM with the residual error correction capability of Gradient Boosting Machine.

---

# 📷 Results

Predicted electricity load closely follows the actual demand across all seasons.

The repository includes prediction graphs for:

- GRU
- LSTM
- Random Forest
- GBM
- Hybrid LSTM + GBM

inside the **results/** folder.

---

# 💡 Applications

- Smart Grid Systems
- Load Forecasting
- Energy Management
- Demand Response
- Utility Planning
- Renewable Energy Integration
- AI-driven Energy Analytics

---

# 🔮 Future Work

- Transformer-based Time-Series Models
- Temporal Fusion Transformer (TFT)
- Informer
- Autoformer
- Weather-aware Forecasting
- Multi-region Forecasting
- Real-time Deployment on AWS
- IoT-based Smart Energy Monitoring

---

# 📚 Research Paper

This project is accompanied by an IEEE-style research paper documenting the methodology, experiments, and comparative analysis.

📄 **Research Paper**

`reports/Research_Paper.pdf`

---

# 👨‍💻 Author

**Sharafat Kothariya**

Computer Engineering Student

AI/ML • Deep Learning • Computer Vision • AWS Cloud

LinkedIn: https://www.linkedin.com/in/sharafatk1/

GitHub: https://github.com/sharafatk1

---

⭐ If you found this project interesting, consider giving it a Star!
