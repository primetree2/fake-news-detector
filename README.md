# fake-news-detector
Using TF-IDF and Text Classification to detect fake news


## Description
The **Fake News Detector** is a lightweight web application that identifies whether a news article is **real** or **fake**.  
It uses **TF-IDF vectorization** and **Multinomial Naive Bayes** for text classification. Users can input **news text** or a **news URL**, and the app predicts its authenticity.

---

## Features
- Input news **text** or **URL**
- Preprocessing: remove punctuation, lowercase, remove stopwords
- Feature extraction with **TF-IDF**
- Classification using **Naive Bayes**
- Lightweight and modular project structure
- Clean, easy-to-read frontend using HTML/CSS/Bootstrap

---

## Tech Stack
- **Backend:** Python, Flask  
- **Machine Learning:** scikit-learn (TF-IDF + Naive Bayes)  
- **Frontend:** HTML, CSS, Bootstrap  
- **Other Libraries:** pandas, numpy, requests, BeautifulSoup4

---

## Installation

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd fake-news-detector
