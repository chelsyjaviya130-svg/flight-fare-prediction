# ✈️ AeroFare – Flight Price Prediction Using Machine Learning

AeroFare is a Machine Learning project that predicts estimated flight ticket prices based on flight details. It uses a trained Random Forest Regression model and an interactive Streamlit web application.

## 🚀 Project Links

- **GitHub Repository:** [https://github.com/chelsyjaviya130-svg/flight-fare-prediction](https://github.com/chelsyjaviya130-svg/flight-fare-prediction)
- **Team Live Demo:** [https://flight-fare-prediction-qb3btfdwzcnxafen8wttqj.streamlit.app/](https://flight-fare-prediction-qb3btfdwzcnxafen8wttqj.streamlit.app/)
- **Model and Dataset:** [https://huggingface.co/shaswat44/flight-price-prediction-files](https://huggingface.co/shaswat44/flight-price-prediction-files)

## 📌 Project Overview

Flight ticket prices vary depending on airline, travel class, route, departure and arrival times, journey duration, and the number of stops.

AeroFare uses Machine Learning to estimate flight fares from available flight information. The application allows users to enter flight details and view a predicted price.

**Note:** Predictions are estimates based on the training data and are not live airline prices.

## ✨ Features

- Interactive Streamlit web application
- Flight fare prediction using Machine Learning
- Flight route and airline details
- Travel class selection
- Departure and arrival time inputs
- Journey duration and stop information
- Model comparison and evaluation
- User-friendly interface

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Web Framework:** Streamlit
- **Machine Learning:** Scikit-learn, Random Forest Regression
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Model Storage:** Joblib
- **Development Environment:** Jupyter Notebook

## ⚙️ How It Works

1. Flight data is prepared and processed.
2. A Machine Learning model is trained using historical flight data.
3. The trained model is used by the Streamlit application.
4. Users enter flight details in the application.
5. The model estimates the flight ticket price.

## 📂 Main Project Files

- `app.py` — Streamlit web application
- `compare_models.py` — Model comparison script
- `requirements.txt` — Python dependencies
- `test_*.py` — Model and prediction tests
- `.gitignore` — Files and folders excluded from Git tracking

The trained model and processed dataset are stored separately. Refer to the Model and Dataset link above for access to those files.

## 💻 Run the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/chelsyjaviya130-svg/flight-fare-prediction.git
cd flight-fare-prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Download the required model and dataset

Download the model and dataset from the Model and Dataset link. Place them in the file paths expected by `app.py`.

### 4. Run the application

```bash
streamlit run app.py
```

## ⚠️ Limitations

- Predictions depend on the available training data.
- The application does not provide live airline ticket prices.
- Actual prices may differ because airline fares change over time.

## 👥 Author

'' javiya chelsy''

## 🎓 Internship

Developed as part of the **Data Science Internship at Naviotech Solution**.

---

**AeroFare — Smarter Flight Fare Estimation**

