# 🎬 IMDB Movie Success Prediction System

## 📌 Project Overview

This project is a **Movie Success Prediction System** built using the IMDB Top 1000 dataset.

The system analyzes movies and classifies them into:

- Blockbuster  
- Hit  
- Average  
- Flop  

It combines:

- Data Cleaning  
- Sentiment Analysis (VADER)  
- Machine Learning (Linear Regression)  
- Flask Web Application  

---

## 🛠 Tools Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK & VADER  
- Flask  
- Jupyter Notebook  

---

## 📊 What Is Done In This Project

- Cleaned IMDB dataset  
- Converted Gross revenue to numeric format  
- Performed genre-wise analysis  
- Applied Sentiment Analysis on movie overview  
- Built Linear Regression model to predict box office  
- Created revenue-based success classification  
- Developed Flask web dashboard  

---

## 📓 What The Jupyter Notebook Contains

**File:** `Movie success prediction.ipynb`

The notebook includes:

- Data loading from IMDB dataset  
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Sentiment analysis using VADER  
- Feature selection (Rating, Votes, Sentiment Score)  
- Linear Regression model building  
- Model evaluation using R² Score and MSE  
- Success classification logic  

---

## ▶️ How To Run This Project (Very Simple Steps)

### 1️⃣ Open VS Code

- Open VS Code  
- Click **File → Open Folder**  
- Select this project folder  

Make sure these files are present:

- `app.py`  
- `imdb_top_1000.csv`  
- `requirements.txt`  

### 2️⃣ Open Terminal Inside VS Code

Click:
Terminal → New Terminal

### 3️⃣ Install Required Libraries

Run:
pip install -r requirements.txt

### 4️⃣ Run The Flask Application
python app.py

### 5️⃣ Open In Browser
After running, open your browser and go to:
http://127.0.0.1:5000

The Movie Success Dashboard will open.

### 📈 Conclusion

This project demonstrates how data analysis, sentiment analysis, and machine learning can be integrated into a Flask web application to evaluate movie success.

It shows a complete end-to-end Data Science workflow from dataset preprocessing to model deployment.

#### 👩‍💻 Author:
Chandana Gowri

Data Analytics & Machine Learning Project
