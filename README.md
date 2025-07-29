
# 🌍 Natural Disaster Prediction using Machine Learning

This project aims to predict natural disasters—such as earthquakes, floods, and hurricanes—based on geographical and environmental data using machine learning models. It supports both classification (disaster type and risk level) and regression (earthquake magnitude, flood water level) tasks.

---

## 🚀 Features

- 🌪️ Predicts type of disaster based on latitude and longitude
- 📊 Classifies the disaster and its risk level (e.g., low, medium, high)
- 📈 Regression models for predicting earthquake magnitude and flood water levels
- 🧠 Uses Random Forest and Decision Tree models
- 🧬 Dimensionality reduction using PCA 
- 💻 Interactive user interface using Streamlit

---

## 🗂️ Project Structure

```
📁 disaster-prediction-ml/
├── data/                  # Raw and preprocessed datasets
├── models/                # Trained models and checkpoints
├── notebook/              # Jupyter notebooks for model training and evaluation
├── app/                   # Streamlit app files
├── utils/                 # Helper functions for preprocessing, visualization, etc.
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## 📌 Dataset

- **Source**: Kaggle
- **Types**: 
  - Atlantic Hurricane Dataset
  - Earthquake Dataset (1990–2023)
  - Flood Risk in India Dataset
- **Features**:
  - Latitude, Longitude
  - Disaster type
  - Magnitude/Water level
  - Time-based and location-based parameters

---

## 🧪 Models Used

| Task | Model | Purpose |
|------|-------|---------|
| Classification | Random Forest | Predicts disaster type and risk level |
| Classification | Decision Tree | Alternative model for interpretability |
| Regression | Random Forest Regressor | Predicts earthquake magnitude, water levels |
| Dimensionality Reduction | PCA & LDA | Improves visualization and model performance |

---

## 📈 Results

- PCA shows clear clusters by disaster type
- Top 2 principal components explain over 50% of variance
- High accuracy in classification tasks (based on test set)
- Streamlit app provides real-time predictions from user input

---

## 🖥️ Streamlit Web App

The app allows users to input:
- Latitude
- Longitude

It returns:
- Predicted disaster type
- Risk level (Low / Medium / High)
- Predicted magnitude or water level (if applicable)

To run the app:

```bash
cd app/
streamlit run app.py
```

---

## 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/disaster-prediction-ml.git
cd disaster-prediction-ml
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📚 Future Work

- Add more disaster types (e.g., landslides, droughts)
- Integrate real-time data APIs
- Include satellite image-based prediction
- Deploy app to the cloud (e.g., Heroku or AWS)

---

## 🙌 Acknowledgements

- Datasets from Kaggle and UCGS
- Streamlit for web app interface
- Scikit-learn for ML models
- Project guided by academic coursework



⭐ *If you like this project, give it a star on GitHub!*
