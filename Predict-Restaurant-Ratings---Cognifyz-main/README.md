# ⭐ Predict Restaurant Ratings — Cognifyz

## 📌 Project Overview

The **Predict Restaurant Ratings — Cognifyz** project is a **machine learning regression-based system** that predicts the **aggregate ratings of restaurants** based on various features such as votes, cuisines, location, price range, and reviews.

In this project, **six different regression algorithms** are implemented and compared using evaluation metrics. Additionally, the most important features contributing to predictions are extracted from the **top two performing models**.

---

## 👨‍💻 Author

**Shivendra Singh Dangi**

* 🎓 B.Tech in **Artificial Intelligence** (Final Year Student)
* Interested in **Machine Learning, Predictive Analytics, and AI-driven solutions**
* Enthusiastic about applying ML techniques to solve **real-world data problems**

---

## 🚀 Features

* ✅ Predicts restaurant ratings using **6 regression algorithms**
* ✅ Displays **evaluation metrics** (RMSE, R² score, MAE, etc.)
* ✅ Extracts **feature importance** for model interpretability
* ✅ Compares performance of all models
* ✅ Highlights the **top 2 best-performing algorithms**

---

## 🛠️ Tech Stack

* **Programming Language**: Python 🐍
* **Libraries Used**:

  * `pandas` – Data manipulation
  * `numpy` – Numerical computations
  * `scikit-learn` – Regression models & evaluation metrics
  * `matplotlib` / `seaborn` – Data visualization
  * `xgboost` / `lightgbm` – Advanced regressors

---

## 📂 Project Structure

```
Predict-Restaurant-Ratings-Cognifyz/
│
├── data/                         # Dataset (CSV files)
├── notebooks/                    # Jupyter notebooks (experiments)
└── README.md                     # Documentation
```

---

## ⚙️ Implementation Details

### 🔹 Algorithms Implemented

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **Gradient Boosting Regressor**
5. **XGBoost Regressor**
6. **LightGBM Regressor**

### 🔹 Evaluation Metrics

* **RMSE** (Root Mean Squared Error)
* **R² Score**
* **MAE** (Mean Absolute Error)

### 🔹 Feature Importance

* Extracted from **Decision Tree, Random Forest, Gradient Boosting, XGBoost, and LightGBM**
* Shows **top 15 influential features** for the **top 2 models**

---

## ⚙️ Installation & Usage

### 1️⃣ Clone Repository

```bash
git clone https://github.com/shivendrai/Predict-Restaurant-Ratings-Cognifyz.git
cd Predict-Restaurant-Ratings-Cognifyz
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Training & Evaluation

```bash
python src/train_models.py
```

---

## 📊 Example Output

**Linear Regression Performance:**

* RMSE: 0.310
* R² Score: 0.952

**Decision Tree Regression Performance:**

* RMSE: 0.275
* R² Score: 0.967

**Top 15 Influential Features (Decision Tree):**

```
Votes                1.865547
Restaurant ID        0.086416
Cuisines             0.072318
Average Cost         0.055214
... (more features)
```

---

## 🔮 Future Enhancements

* ⚡ Hyperparameter tuning using **GridSearchCV / Optuna**
* 📈 Cross-validation for robust performance evaluation
* 🌍 Deploy the model via **Flask / Streamlit** for user interaction
* 🧠 Explore **Deep Learning (Neural Networks)** for prediction

---

## 🤝 Contributing

Contributions are welcome! Please **fork** the repo and create a **pull request** with your improvements.

---

## 📜 License

This project is licensed under the **MIT License** – free to use and modify.

---

✨ *Developed with dedication by* **Shivendra Singh Dangi** ✨

---