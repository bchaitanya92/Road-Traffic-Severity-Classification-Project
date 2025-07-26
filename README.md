# 🚧 Road Traffic Severity Classification

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/scikit--learn-F7931A?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">
</p>

<p align="center">
  <b>Predict the severity of road accidents using machine learning and interactive web apps.</b><br>
  <i>Empowering safer roads through data-driven insights and explainable AI.</i>
</p>

---

## 📊 Project Overview

This project is a multiclass classification solution that predicts the severity of road accidents—**Fatal**, **Serious**, or **Slight**—based on real-world data from Addis Ababa, Ethiopia (2017–2020). The dataset contains 32 features and 12,316 instances, curated from police records.

The web application is built with **Streamlit** and leverages **scikit-learn** for modeling and **SHAP** for explainable AI, allowing users to interactively explore predictions and understand the factors influencing accident severity.

---

## 🗂️ Repository Structure

```
Road-Traffic-Severity-Classification-Project/
│
├── app.py                  # Streamlit web app source
├── requirements.txt        # Python dependencies
├── rta_model_deploy3.joblib      # Trained ML model
├── ordinal_encoder2.joblib       # Ordinal encoder for categorical features
├── background.webp         # App background image
├── data/                   # (Optional) Data files
├── src/                    # (Optional) Source scripts
└── README.md               # Project documentation
```

---

## 🚦 Features

- **Interactive Web App:** User-friendly interface for accident severity prediction.
- **Explainable AI:** SHAP visualizations to interpret model decisions.
- **Customizable Inputs:** Select accident details and instantly see predictions.
- **Real-World Data:** Based on actual police records from Addis Ababa.

---

## 🚀 Getting Started

### 1. Prerequisites

- Python 3.8 or higher
- `pip` package manager

### 2. Installation

Clone the repository:
```sh
git clone [https://github.com/sumitsartale4952/Road-Traffic-Severity-Classification.git](https://github.com/bchaitanya92/Road-Traffic-Severity-Classification-Project.git)
cd Road-Traffic-Severity-Classification
```

Install dependencies:
```sh
pip install -r requirements.txt
```

### 3. Run the App

```sh
streamlit run app.py
```

The app will open in your browser. Adjust input fields and click **Predict** to see the accident severity and SHAP explanations.

---

## 🧠 How It Works

1. **User Input:** Enter accident details (vehicles involved, casualties, time, driver info, etc.).
2. **Prediction:** The trained model predicts the severity class.
3. **Explanation:** SHAP force plots show which features most influenced the prediction.

---

## 📚 Dataset

- **Source:** Addis Ababa Sub-city police departments (2017–2020)
- **Features:** 32 (demographics, accident context, vehicle info, etc.)
- **Target:** `Accident_severity` (Fatal, Serious, Slight)

---

## 👨‍💻 Author & Credits

Developed by:  **B. Chaitanya**  

- GitHub: [bchaitanya92](https://github.com/bchaitanya92)
- LinkedIn: [BOURISETTI CHAITANYA](https://www.linkedin.com/in/bourisetti-chaitanya/)

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is open source. Feel free to use, modify, and distribute it as you see fit.

---

<p align="center">
  <b>Drive safe. Predict smart.</b><br>
  <i>Road Traffic Severity Classification Project</i>
</p>
