# Krishak-The_Crop_Recommender

## 📌 Project Overview

This is a **Flask-based web application** that recommends the best crop for cultivation based on soil nutrients, weather conditions, and rainfall. It utilizes a **Machine Learning model (Random Forest)** for prediction and fetches real-time weather data using the **OpenWeatherMap API**.

## 🏗️ Features

✅ User-friendly web interface built with **Flask**.\
✅ Accepts input parameters: **Nitrogen, Phosphorous, Potassium, pH, Rainfall, and City Name**.\
✅ Fetches **real-time temperature and humidity** from OpenWeatherMap API.\
✅ Uses **Random Forest Classifier** for crop prediction.\
✅ Displays **best-suited crop recommendation** for the given inputs.

## 🛠️ Tech Stack

- **Python** (Flask, NumPy, Pandas, Pickle)
- **Machine Learning** (Random Forest Model)
- **OpenWeatherMap API** (Weather Data)
- **HTML, CSS, Bootstrap** (Frontend)

## 📥 Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-repo/crop-recommendation.git
cd crop-recommendation
```

### 2️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

### 3️⃣ Add OpenWeatherMap API Key

- Create a `config.py` file inside the project directory.
- Add your API key:

```python
weather_api_key = "your_openweathermap_api_key"
```

### 4️⃣ Run the Flask Application

```bash
python app.py
```

- Open your browser and go to `http://127.0.0.1:8000/`

## 🚀 Usage

1️⃣ Visit the **Crop Recommendation Page**.\
2️⃣ Enter soil details (**Nitrogen, Phosphorous, Potassium, pH, Rainfall**).\
3️⃣ Enter your **City Name** to fetch live weather data.\
4️⃣ Click **Predict**, and the model will suggest the best crop to grow.

## 📊 Machine Learning Model

- **Algorithm:** Random Forest Classifier
- **Input Features:** Nitrogen, Phosphorous, Potassium, Temperature, Humidity, pH, Rainfall
- **Trained Model File:** `models/RandomForest.pkl`

## 🎯 Future Improvements

🔹 Use a **more advanced ML model (XGBoost, Deep Learning)**.\
🔹 Integrate a **database** to store user inputs and past recommendations.\
🔹 Improve the **frontend UI** for better user experience.\
🔹 Allow **seasonal recommendations** based on the planting cycle.


