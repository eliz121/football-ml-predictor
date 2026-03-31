# ⚽ Football Match Prediction using Machine Learning & Poisson Models

## 📌 Project Overview

This project aims to predict football match outcomes (Home Win, Draw, Away Win) using Machine Learning techniques combined with statistical models such as the Poisson distribution.

The system integrates historical match data, team performance metrics, and economic indicators (team market values) to generate probabilistic predictions.

---

## 🎯 Objectives

* Predict match outcomes using ML classification models
* Estimate expected goals (λ) for each team
* Apply Poisson distribution to simulate match results
* Analyze feature importance in football predictions
* Build a scalable model adaptable to different leagues and tournaments (e.g., World Cup)

---

## 🧠 Methodology

### 1. Data Collection

* Historical match data (scores, teams, dates)
* Team statistics (form, goals, performance)
* Market values (Transfermarkt)

### 2. Feature Engineering

* Average goals (last matches)
* Goals conceded
* Team form (W/D/L encoded)
* Home advantage
* Team value ratio

### 3. Models Used

* Logistic Regression
* Random Forest / XGBoost
* Poisson Distribution for goal prediction

### 4. Prediction Approach

* ML model predicts match outcome probabilities
* Poisson model estimates score distributions
* Combined approach improves accuracy

---

## 📊 Project Structure

```
football-ml-predictor/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── exploration.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── predict.py
│
├── models/
├── results/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

1. Prepare dataset in `/data`
2. Run preprocessing:

```bash
python src/data_preprocessing.py
```

3. Train model:

```bash
python src/train_model.py
```

4. Make predictions:

```bash
python src/predict.py
```

---

## 📈 Evaluation Metrics

* Accuracy
* Log Loss
* Confusion Matrix

---

## 🔥 Future Improvements

* Integrate real-time data APIs
* Include expected goals (xG)
* Add betting odds comparison
* Expand to international tournaments (World Cup)

---

## 📚 Technologies

* Python
* Scikit-learn
* Pandas / NumPy

---

## 👩‍💻 Author

Elizabeth Mendoza

---

## ⚠️ Disclaimer

This project is for educational and research purposes only. Predictions are not guaranteed and should not be used as financial advice.
