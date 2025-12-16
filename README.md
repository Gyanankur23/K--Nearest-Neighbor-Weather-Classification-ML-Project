# K--Nearest-Neighbor-Weather-Classification-ML-Project


## 🌦️ K-Nearest-Neighbor Weather Classification

This Streamlit app demonstrates how the K-Nearest Neighbors (KNN) algorithm can be used to classify weather conditions (Sunny 🌞 or Rainy 🌧️) based on temperature and humidity values.

---

## 📖 Overview
- Built with Python, Streamlit, scikit-learn, and Matplotlib.
- Uses a small training dataset of temperature & humidity values.
- Provides interactive sliders for user input.
- Visualizes classification results and prediction confidence.

---

## 🚀 Features
- Interactive Sidebar: Input temperature, humidity, and number of neighbors (K).
- Real-time Prediction: Displays predicted weather condition with confidence score.
- Visualization: Scatter plot showing training data and new prediction point.
- Model Info: Summary of training data, current input, and probability distribution.
- Expandable Info Section: Explains what KNN is and how it works.

---

## 🛠️ Installation

Clone the repository and install dependencies:

`bash
git clone <your-repo-link>
cd <your-repo-folder>
pip install -r requirements.txt
`

## Requirements
- Python 3.8+
- Streamlit
- scikit-learn
- numpy
- matplotlib

---

## ▶️ Usage

Run the app locally:

`bash
streamlit run app.py
`

Open the app in your browser at http://localhost:8501.

---

## 📊 Example

- Sunny → High temperature + Low humidity  
- Rainy → Low temperature + High humidity  

The app uses a simple dataset:

| Temperature (°C) | Humidity (%) | Label  |
|------------------|--------------|--------|
| 30               | 70           | Sunny  |
| 25               | 80           | Rainy  |
| 27               | 60           | Sunny  |
| 31               | 65           | Sunny  |
| 23               | 85           | Rainy  |
| 28               | 75           | Rainy  |

---

### ℹ️ What is KNN?

K-Nearest Neighbors (KNN) is a supervised machine learning algorithm used for classification and regression.

How it works:
1. Training: Stores all training data points with labels.  
2. Prediction:  
   - Calculates distance to all training points.  
   - Finds the K closest neighbors.  
   - Uses majority vote (classification) or average (regression).  

Key Parameters:
- Temperature: Input temperature for prediction.  
- Humidity: Input humidity for prediction.  
- K: Number of neighbors considered.  

---

### 📌 Links
- Streamlit Documentation  
- scikit-learn KNN  
- Matplotlib  

(Add your repo link, demo video, or deployment link here once ready)

---

### 📝 License
This project is open-source. Feel free to use and adapt it for learning purposes.
`
