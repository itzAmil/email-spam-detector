#  Email Spam Detection Using Machine Learning

Email Spam Detection is a Machine Learning project designed to classify emails as **Spam** or **Not Spam** based on their textual content.

The system leverages natural language processing techniques and traditional ML models to identify patterns in email data and detect spam effectively. It includes a Streamlit-based frontend that allows users to input email text and receive instant classification results.

---

## 🚀 Features

- Email preprocessing: lowercase conversion, punctuation removal
- Feature extraction using TF-IDF Vectorizer
- Multiple ML models trained and compared
- Final deployed model: Naive Bayes
- Live prediction frontend built with Streamlit
  
---

## 🧠 Models Trained & Evaluated

The following models were trained and evaluated using accuracy and precision metrics:

- ✅ Naive Bayes
- ✅ Logistic Regression
- ✅ Support Vector Machine (SVM)
- ✅ Decision Tree Classifier

> ✅ **Final Model** used in the Streamlit frontend : **Naive Bayes**

---

## 🧰 Tech Stack

- Python 3.13
- Streamlit
- scikit-learn
- pandas
- pickle
- nltk 

---

## 📁 Dataset

- File: `mail_data.csv`
- Contains labeled email text data with 'label' (spam/ham) and 'text' column.

---

## 🚦 How It Works

1. User inputs email text into the Streamlit frontend.
2. The text is transformed using the trained TF-IDF vectorizer.
3. The vectorized input is passed to the Naive Bayes model.
4. The model outputs `Spam` or `Not Spam` as the prediction.

---

## 👥 Contributors

This project was originally developed as part of a group academic project.

**Original Contributors:**
- Amil Gauri (Maintainer)
- Vikas Pandit  
- Jayesh Patil  
- Ajay Chaurasiya  

> Project restructured, documented, and maintained by **Amil Gauri** for public release.

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).  
You are free to use, modify, and distribute it with proper credit.

See the LICENSE file for full details.

---
