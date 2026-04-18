# 🏠 Housing Price Prediction Web App

A Machine Learning web application built using **Flask** that predicts housing prices based on user input features.
This project demonstrates end-to-end ML workflow: data preprocessing, model training, and deployment.

---

## 🚀 Features

* Predict house prices using a trained ML model
* Clean and interactive web interface
* Handles numerical and categorical features
* Uses Scikit-learn Pipeline for preprocessing
* Easy to run locally

---

## 🛠️ Tech Stack

* Python
* Flask
* Scikit-learn
* Pandas & NumPy
* HTML & CSS

---

## 📂 Project Structure

```bash id="zz8g1s"
project/
│
├── app.py              # Flask web application
├── main.py             # Model training script
├── housing.csv         # Dataset
├── requirements.txt
├── README.md
│
└── templates/
    └── index.html      # Frontend UI
```
 ## Dataset link:-
 https://www.kaggle.com/datasets/camnugent/california-housing-prices
---

## ⚠️ Important Note

The trained files:

* `model.pkl`
* `pipeline.pkl`

are **not included in this repository** due to file size limitations and best practices.

---

## 🧠 How to Run the Project

### Step 1: Clone the repository

```bash id="sx8r3g"
git clone <your-repo-link>
cd project
```

---

### Step 2: Install dependencies

```bash id="t5c1qk"
pip install -r requirements.txt
```

---

### Step 3: Train the model

```bash id="pjwz0u"
python main.py
```

This will generate:

```bash id="5z7zj9"
model.pkl
pipeline.pkl
```

---

### Step 4: Run the Flask app

```bash id="n8r6o2"
python app.py
```

---

### Step 5: Open in browser

```id="n6z7gx"
http://127.0.0.1:5000/
```

---

## 📊 Input Features

* Longitude
* Latitude
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Ocean Proximity

---

## 📌 Output

* Predicted median house value

---

## 👨‍💻 Author

**Sumandeep Prasad**

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
