# 🌸 Iris Flower Classifier

A machine learning web app that predicts the species of an Iris flower based on its measurements.

## 🔗 Live Demo
👉 [https://owais-flower-classifier.onrender.com](https://owais-flower-classifier.onrender.com)

## 🚀 What it does
- Takes 4 flower measurements as input (sepal length, sepal width, petal length, petal width)
- Predicts the Iris species: **Setosa**, **Versicolor**, or **Virginica**
- Shows confidence percentage for all 3 classes with an interactive bar chart

## 🛠️ Tech Stack
| Layer | Technology |
|---|---|
| Backend | Python, FastAPI |
| ML Model | Logistic Regression (scikit-learn) |
| Frontend | HTML, CSS, JavaScript, Chart.js |
| Dataset | Iris Dataset (built into scikit-learn) |
| Deployment | Render |

## 📁 Project Structure
```
iris-classifier/
├── main.py            # FastAPI backend + ML model
├── index.html         # Frontend UI with Chart.js graph
└── requirements.txt   # Python dependencies
```

## 📊 Model Performance
- **Algorithm:** Logistic Regression
- **Test Accuracy:** ~97%
- **Dataset:** 150 samples, 3 classes, 4 features

## ⚙️ How to Run Locally

**1. Clone the repo**
```bash
git clone https://github.com/yourusername/iris-classifier.git
cd iris-classifier
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the server**
```bash
uvicorn main:app --reload
```

**4. Open in browser**
```
http://127.0.0.1:8000
```

## 📸 Sample Input
| Field | Value |
|---|---|
| Sepal Length | 5.1 |
| Sepal Width | 3.5 |
| Petal Length | 1.4 |
| Petal Width | 0.2 |

**Result → Setosa (99.9% confidence)**

## 👨‍💻 Author
**Mohammad Owais Maroof**
B.Tech CSE (Data Science) — Jamia Millia Islamia
[LinkedIn](https://linkedin.com/in/owais-maroof)
