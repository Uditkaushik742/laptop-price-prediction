# 💻 Laptop Price Prediction for SmartTech Co.

This machine learning project predicts laptop prices based on hardware specifications like processor type, RAM, storage, and screen size. Built for SmartTech Co., the model assists in setting competitive prices in the market using regression algorithms.

---

## 📊 Project Overview

In a rapidly evolving tech market, pricing laptops effectively requires data-driven insights. This project builds a predictive model using historical data and regression techniques on Google Colab.

---

## 📁 Project Structure

- `laptop_model.ipynb` – Google Colab notebook with full model pipeline
- `laptop.csv` – Dataset containing specifications and prices of laptops
- `presentation.pptx` – Business presentation covering approach and results

---

## 📈 Key Features

- **Data Preprocessing**: Handled missing values, categorical encoding, and feature scaling
- **Modeling**:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- **Evaluation**: Compared models using R², MAE, and RMSE

---

## 📌 Results

- Best model achieved an R² score of **0.92**
- Key features influencing price: processor type, RAM, and brand

---

## 🛠️ Tech Stack

- **Platform**: Google Colab
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

---

## 📎 Dataset

The dataset includes laptop specs such as:
- Processor
- RAM
- Storage
- Screen Size
- Brand
- Price

---

## 📢 Presentation

Included in `presentation.pptx`, highlighting:
- Business problem
- Data insights
- Model performance
- Recommendations

---

## 🚀 Future Enhancements

- Deploy as a Streamlit or Flask app
- Add scraping to pull current laptop data from e-commerce platforms
