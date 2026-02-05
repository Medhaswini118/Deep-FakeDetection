# Deepfake Detection on Social Media

Detecting machine-generated (bot) tweets using **FastText embeddings**, **Machine Learning**, and **Deep Learning (CNN)**, deployed through a **Django web application**.

---

## 🔍 Project Description

With the rise of AI-generated text and social media bots, identifying fake content has become critical.  
This project classifies tweets as **Human** or **Bot-generated** by leveraging:

- Natural Language Processing (NLP)
- FastText word embeddings
- Traditional ML classifiers
- Convolutional Neural Networks (CNN)
- A web interface built using Django

---

## ✨ Key Features

- Load and preprocess tweet datasets
- Generate FastText embeddings
- Train multiple ML models
- Implement deep learning (CNN & Hybrid CNN)
- Compare algorithms using performance metrics
- Real-time fake tweet detection via web UI

---

## 🧠 Tech Stack

### Language
- **Python 3.7.x** (required)

### Frameworks & Libraries
- **Django 2.1.7** – Web framework
- **TensorFlow 1.14 + Keras 2.3.1** – Deep learning
- **FastText** – Word embeddings
- **NLTK** – Text preprocessing
- **Scikit-learn** – ML algorithms & metrics
- **Pandas, NumPy** – Data processing
- **Matplotlib** – Graphs & evaluation
- **SQLite** – Database

---


## 📂 Project Structure

DeepFake/

├── Dataset/       # Tweet dataset

├── Deep/          # Django project settings

├── DeepApp/       # Django application logic

├── model/         # Saved trained models

├── images/        # Screenshots and result images

├── manage.py      # Django entry point

├── requirements.txt # Python dependencies

├── db.sqlite3     # SQLite database

├── run.bat        # Project launcher (Windows)

├── nltkdownload.py # NLTK resource downloader

└── README.md

---

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/deepfake-detection-social-media.git
cd deepfake-detection-social-media
```
(or) Download Zip

### 2. Install Python 3.7.x

Download from:
```bash
https://www.python.org/downloads/release/python-379/
```
⚠️ This project is not compatible with Python 3.8+ due to TensorFlow 1.x.
✔️ Make sure **“Add Python to PATH”** is checked during installation.

Verify:
```bash
python --version
```
### 3. Create Virtual Environment
```bash
  python -m venv venv
```
Activate:
```bash
  venv\Scripts\activate
```
### 4. Install Dependencies
```bash
    pip install -r requirements.txt
```
### 5. Download NLTK Resources (IMPORTANT)
This project uses stopwords and WordNet.
Run:
  ```bash
  python nltkdowload.py
```
OR manually:
```bash
  import nltk
  nltk.download('stopwords')
  nltk.download('wordnet')
```
### 6. Database Migration
```bash
    python manage.py migrate
```
### 7. Running the Project
Start Django Server
```bash
    python manage.py runserver
```
Open browser:
```bash
    http://127.0.0.1:8000/index.html
```

## 📊 Algorithms Implemented

### Traditional Machine Learning
- Naive Bayes
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

### Deep Learning (Proposed)
- CNN with FastText embeddings
- Hybrid CNN (Extended model)

---

## 📈 Performance Summary

| Model               | Accuracy (%) |
|--------------------|--------------|
| Naive Bayes         | 52.5         |
| Logistic Regression | 58.5         |
| Decision Tree       | 60.0         |
| Random Forest       | 61.5         |
| Gradient Boosting   | 54.0         |
| Proposed CNN        | 88.31        |
| Hybrid CNN          | 96.38        |

---

## 🧪 Example Tweets

### Human
> Had a wonderful interaction with leaders and MPs across party lines.

### Bot
> The configuration process enables execution of distributed runtime components.

---

## 📸 Screenshots

### Example Tweet
### Output Screen





