# **Spotify Viral Song Analysis**

## Overview

Project ini bertujuan untuk menganalisis faktor-faktor yang mempengaruhi apakah sebuah lagu dapat menjadi viral.

Analisis ini relevan untuk:

* 🎵 Music label → menentukan strategi rilisan
* 🎤 Artist → memahami karakter lagu populer
* 📱 Platform streaming → sistem rekomendasi

---

## 📊 Dataset

Dataset berisi berbagai fitur audio dari lagu, seperti:

* **Danceability** → tingkat kemudahan lagu untuk ditarikan
* **Energy** → intensitas lagu
* **Valence** → tingkat emosi positif
* **Tempo** → kecepatan lagu
* **Duration** → durasi lagu

Target:

* **Viral (1 = viral, 0 = tidak)**

---

## 🔍 Exploratory Data Analysis

Beberapa temuan awal:

* Hanya sebagian kecil lagu yang menjadi viral
* Lagu viral cenderung memiliki **energy lebih tinggi**
* Kombinasi **danceability dan energy** cukup berpengaruh

---

## ⚙️ Feature Engineering

Fitur tambahan yang dibuat:

* `energy_dance_ratio`
* `mood_score`
* `duration_min`

---

## 🤖 Modeling

Model yang digunakan:

* Logistic Regression
* Random Forest
* XGBoost

---

## 📈 Evaluation

Model terbaik: **(ISI PUNYA KAMU)**

Alasan:

* (ISI ANALISIS KAMU, ini penting banget)

---

## 💡 Key Insights

* Faktor paling berpengaruh: **(isi)**
* Karakter lagu viral: **(isi)**
* Model terbaik: **(isi)**

---

## 📁 Project Structure

```
spotify-viral-analysis/
│
├── data/
├── notebook/
├── images/
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 👤 Author

Rahma Sakinah
