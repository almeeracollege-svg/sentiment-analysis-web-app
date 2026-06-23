```md
# Sentiment Analysis Web App

A web application built using **Flask** and **TextBlob** that analyzes user-entered text and predicts whether the sentiment is **Positive, Negative, or Neutral**.

---

## 🚀 Live Demo

👉 https://sentiment-analysis-web-app-cba3.onrender.com/

---

## 📌 Features

- Sentiment Classification (Positive / Negative / Neutral)
- Polarity Score Analysis
- Real-time Prediction
- Simple and User-Friendly Interface

---

## 🛠️ Technologies Used

- Python
- Flask
- TextBlob
- HTML
- CSS

---

## 📁 Project Structure

```

sentiment-analysis-web-app/
│
├── app.py
├── requirements.txt
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css

````

---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/almeeracollege-svg/sentiment-analysis-web-app.git
````

### 2. Navigate to project folder

```bash
cd sentiment-analysis-web-app
```

### 3. Create virtual environment (optional)

```bash
python -m venv venv
```

Activate environment:

Windows:

```bash
venv\Scripts\activate
```

Mac/Linux:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install flask textblob gunicorn
```

### 5. Run the application

```bash
python app.py
```

### 6. Open in browser

```
http://127.0.0.1:5000
```

---

## 🌐 Deployment

This project is deployed using Render.

Build Command:

```
pip install -r requirements.txt
```

Start Command:

```
gunicorn app:app
```

---

## 👨‍💻 Author

* Name: ALMEERA ABDUL SATHAR
* Internship: AI Integrated Full Stack Python Development
```

