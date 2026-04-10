# ⚡ Hourly Power Consumption Forecasting for Smart Home using Time Series Models

## 📌 Project Overview
This project focuses on forecasting hourly electricity consumption using advanced **time series and machine learning models**. The objective is to accurately predict power demand patterns to support smart home energy management and intelligent grid systems.

The study performs a comparative analysis of multiple forecasting models and proposes a **Hybrid LSTM + GBM model**, which achieves the best performance.

---

## 👨‍💻 Team Members
- Sharafathusein Kothariya  
- Shubhra Gupta  
- Anuska Singh  

---

## 📊 Dataset
This project uses the **NYISO (New York Independent System Operator) Hourly Electricity Load Dataset**.

🔗 Dataset Link:  
https://www.nyiso.com/load-data

> The dataset contains hourly electricity demand data across multiple zones and is widely used for energy forecasting research. :contentReference[oaicite:0]{index=0}

---

## 🚀 Models Implemented
The following models were implemented and compared:

- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Gradient Boosting Machine (GBM)
- Random Forest (RF)
- 🔥 Hybrid LSTM + GBM (Proposed Model)

---

## 🧠 Methodology
The project follows a complete data science pipeline:

1. Data Collection (NYISO dataset)
2. Data Preprocessing
   - Missing value handling
   - Outlier detection
   - Timestamp processing
3. Feature Engineering
   - Lag features (1h, 24h, 168h, etc.)
   - Rolling statistics
   - Temporal features
4. Model Training
5. Evaluation using:
   - RMSE
   - MAE
   - MAPE
   - R²

---

## 📈 Results
The **Hybrid LSTM + GBM model** achieved the best performance:

- RMSE: 52.50 MW  
- MAE: 35.43 MW  
- MAPE: 0.60%  
- R²: 0.9979 :contentReference[oaicite:1]{index=1}  

This shows a significant improvement over individual models.

---

## 🛠️ Technologies Used
- Python 3
- TensorFlow / Keras
- Scikit-learn
- XGBoost
- Pandas, NumPy
- Matplotlib
- Google Colab (GPU)

---

## ▶️ How to Run the Project

### 📌 Google Colab Implementation
Run the complete project using the Colab notebook:

🔗 **Colab Link:**  
[https://share.google/MN7mkthwA3OTA2RIL](https://colab.research.google.com/drive/1PNfNyuj71rd45G874BfgWG3XKYy9kEeb)

---

### ⚙️ Steps to Run
1. Open the Colab link above  
2. Upload or access dataset from NYISO  
3. Run all cells sequentially  
4. View model training and results  

---

## 📑 Documentation
- 📄 Research Paper: Included in repository  
- 📄 Project Report: Included in repository  

---

## 📌 Key Contribution
The main contribution of this project is the **Hybrid LSTM + GBM model**, which combines:
- LSTM → Temporal pattern learning  
- GBM → Residual error correction  

This significantly improves forecasting accuracy.

---

## 🔮 Future Scope
- Real-time deployment in smart homes  
- Integration with IoT devices  
- Inclusion of weather data  
- Cloud-based energy prediction systems  

---

## 📚 References
- NYISO Dataset (Official Website)
- Research Paper (Included in repository) :contentReference[oaicite:2]{index=2}  

---

## ⭐ Conclusion
This project demonstrates that hybrid models outperform standalone approaches in time series forecasting and can be effectively used for **smart energy management systems**.
