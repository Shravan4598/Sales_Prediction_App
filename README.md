# Sales_Prediction_App


<p align="center">
  <img src="https://streamlit.io/images/brand/streamlit-logo-secondary-colormark-darktext.svg" alt="Streamlit Logo" width="300"/>
</p>

<h1 align="center">Sales Prediction App 📈</h1>

<p align="center">
  A simple and interactive web application to predict sales using machine learning.<br/>
  Built with Python, Streamlit, and Linear Regression.
</p>

---

## 🎥 Demo

<p align="center">
  <img src="https://github.com/Shravan4598/Sales_Prediction_App/blob/main/sales_prediction_app.gif" alt="Demo GIF" width="700"/>
</p>

---

## 🖼️ Screenshots

<p align="center">
  <img src="https://github.com/Shravan4598/Sales_Prediction_App/blob/main/Screenshot%202025-05-07%20011943.png" alt="Screenshot 1" width="700"/>
  <br><br>
  <img src="https://github.com/Shravan4598/Sales_Prediction_App/blob/main/Screenshot%202025-05-07%20012022.png" alt="Screenshot 2" width="700"/>
</p>

---

## 🔗 Live App

👉 [Sales Prediction App (Streamlit)](https://salespredictionshravan.streamlit.app/)

## 📊 Dataset

📥 [Sales Prediction Dataset (Kaggle)](https://www.kaggle.com/code/ashydv/sales-prediction-simple-linear-regression/input)

---

## 🚀 Features

- ✅ User-friendly Streamlit interface
- ✅ Takes input features and predicts sales using multiple ML models
- ✅ Visualizes results in real time
- ✅ Easy to deploy and extend

---

## 🧠 Model Performance Table

| Model                 | MSE (Train) | MSE (Test) | R² (Train) | R² (Test) | Notes                                                       |
| --------------------- | ----------- | ---------- | ---------- | --------- | ----------------------------------------------------------- |
| **Linear Regression** | 2.6761      | 2.9078     | 0.9001     | 0.9059    | —                                                           |
| **Decision Tree**     | 0.0000      | 2.9335     | 1.0000     | 0.9051    | Likely overfitting                                          |
| **Random Forest**     | 0.2319      | 1.4383     | 0.9913     | 0.9535    | Good generalization                                         |
| **XGBoost**           | 0.00000306  | 1.4514     | 1.0000     | 0.9530    | Very close fit                                              |
| **Improved XGBoost**  | 0.00000165  | 1.5453     | 0.99999994 | 0.9500    | Tuned with GridSearchCV (`max_depth=7`, `n_estimators=200`) |

---

### ✅ Why Random Forest Regressor is the Best Choice

1. **💯 Best Generalization (Train/Test Balance)**  
   * Train R² = 0.9913, Test R² = 0.9535 → very close values mean it avoids overfitting and underfitting.  
   * Other models (e.g., Decision Tree and XGBoost) show signs of overfitting.

2. **📉 Lowest Test MSE**  
   * Random Forest achieves **lowest Test MSE = 1.4383**, meaning it's most accurate on unseen data.

3. **📊 Highest Test R²**  
   * Test R² = **0.9535**, better than all other models — it explains over **95%** of test data variance.

4. **🌲 Ensemble Advantage**  
   * As an ensemble of decision trees, it benefits from reduced overfitting and increased robustness.

5. **🚀 Better than Tuned XGBoost**  
   * Despite tuning, Improved XGBoost slightly overfits with a near-perfect Train R² and lower Test R² than Random Forest.

---

## 🛠️ Installation & Running Locally

1. Clone the repository:

  
   git clone https://github.com/Shravan4598/Sales_Prediction_App.git


2. Navigate to the directory:

   ```bash
   cd Sales_Prediction_App
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch the app:

   ```bash
   streamlit run app.py
   ```

   * Local URL: `http://localhost:8501`
   * Network URL (e.g.): `http://192.168.43.182:8502`

---

## 🧰 Technologies Used

* Python 🐍
* Streamlit 🌐
* Pandas 📊
* NumPy ➗
* Scikit-learn 🤖
* XGBoost ⚡
* Matplotlib & Seaborn 📉

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

* 💼 GitHub: [Shravan4598](https://github.com/Shravan4598)
* 📧 Email: [shravankumarpandey825412@gmail.com](mailto:shravankumarpandey825412@gmail.com)

---

<p align="center">
  Made with ❤️ by Shravan Kumar Pandey
</p>
```

---

