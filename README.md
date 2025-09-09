
# EV Charging Demand Forecasting 🚗⚡

An interactive **Streamlit web application** that forecasts **EV charging demand** using **Machine Learning** techniques. This project aims to help charging station operators and energy planners optimize infrastructure and resource allocation.

---

## 📌 Features
- **Forecasting Model**: Built using **Random Forest Regressor** with highly accurate results  
  - **MAE**: 0.01  
  - **RMSE**: 0.06  
  - **R² Score**: 1.00  
- **Interactive Web Interface**: Developed with **Streamlit** for easy use and visualization  
- **Feature Importance Analysis**: Understand factors affecting EV charging demand  
- **Real-time Visualizations**: Line charts and plots for better insights  

---

## 🛠️ Tech Stack
- **Python**  
- **scikit-learn** (Machine Learning)  
- **Streamlit** (Web App)  
- **Matplotlib / Seaborn** (Visualization)  
- **pandas, numpy** (Data Handling)  

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/DeepHansora/EV_Project.git
cd EV_Project
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
conda create -n evp python=3.10
conda activate evp
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Streamlit App
```bash
streamlit run app.py
```

---

## 📊 Results

| Metric        | Value  |
|---------------|--------|
| MAE            | 0.01   |
| RMSE           | 0.06   |
| R² Score       | 1.00   |

The model achieves **near-perfect accuracy** for the given dataset.

---

## 📈 Future Improvements
- Integrate **real-time EV data APIs**  
- Experiment with **XGBoost and LSTM** for time-series forecasting  
- Deploy the app on **Streamlit Cloud or AWS** for public access  

---

## 🎯 Use Case
This project can assist:  
- EV Charging Stations → **Predict peak demand**  
- Energy Planners → **Optimize resource allocation**  
- Researchers → **Analyze EV adoption patterns**  

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
