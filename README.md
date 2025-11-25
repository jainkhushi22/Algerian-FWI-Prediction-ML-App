# 🔥 Algerian Fire Weather Index (FWI) Prediction — ML Web App  

A clean, end-to-end Machine Learning project that predicts the **Fire Weather Index (FWI)** for Algerian forest regions.  
Built with **Flask**, **Ridge Regression**, and **Scikit-Learn**, this app converts raw environmental inputs into a real-time FWI prediction.

---

## 🌿 Why This Project?

Wildfires in Algeria damage forests, ecosystems, and communities every year.  
This project builds a simple, accessible **ML-powered prediction tool** that helps estimate fire risk early using nine environmental parameters.

---

## 🚀 Tech Stack  
- **Python 3**  
- **Flask Web App**  
- **Pandas, NumPy, Scikit-Learn**  
- **Ridge Regression ML Model**  
- **HTML + Jinja Templates**  
- **Render (Free Tier) Deployment**

---

## 🧠 ML Pipeline  
1. Raw dataset → cleaning + preprocessing  
2. Feature scaling using **StandardScaler**  
3. Model training with **Ridge Regression**  
4. Saving models as `.pkl`  
5. Flask backend loads them for live predictions  

Models stored in `models/`:
- `ridge.pkl`
- `scaler.pkl`

---

```
## 📂 Project Structure  

Algerian-FWI-Prediction-ML-App/
│
├── models/ # Saved ML model & scaler
│ ├── ridge.pkl
│ └── scaler.pkl
│
├── notebooks/ # EDA, cleaning & model training notebooks
│ ├── Algerian_forest_fires_cleaned_dataset.csv
│ ├── Algerian_forest_fires_dataset_UPDATE.csv
│ ├── EDA.ipynb
│ ├── Model_train.ipynb
│ └── datacleaning.ipynb
│
├── templates/ # Frontend templates
│ ├── home.html
│ └── index.html
│
├── application.py # Flask backend
├── requirements.txt # Dependencies
└── README.md
```


---

## 🖥️ How It Works  
1. User enters environmental inputs (Temperature, RH, Ws, Rain, etc.)  
2. Data gets scaled using the saved StandardScaler  
3. Ridge Regression model predicts the FWI  
4. Result displayed on the UI (`home.html`)  

---

## 🌍 Deployment (Render)  

Build Command:pip install -r requirements.txt

Start Command: gunicorn application:app

Live Demo:  
👉 https://algerian-fwi-prediction-ml-app.onrender.com/

👉 https://algerian-fwi-prediction-ml-app.onrender.com/predictdata

---


## ✨ Features  
- Smooth Flask UI  
- Fast ML inference  
- Clean repo structure  
- Interactive prediction form  
- Real-world wildfire dataset  

---

## 🧩 Future Upgrades  
- Add fire-risk classification (Low/Med/High)  
- Add charts/visual feedback  
- API-only version for external apps  
- More models: Random Forest, XGBoost  

---
Building practical ML apps with clean code + real-world impact. 💫  

---

## ⭐ Support  
If this project helped you, feel free to **star the repo** ⭐  

