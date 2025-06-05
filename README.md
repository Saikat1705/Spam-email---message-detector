# 📬 Spam Email Detector

This project is a machine learning-based web application that detects whether an email message is spam or not. It uses the SMS Spam Collection Dataset, Scikit-learn's Naive Bayes classifier, and is powered by a user-friendly Streamlit interface.

## 🔍 Features

- Cleans and preprocesses email text using NLP techniques
- Trains a Multinomial Naive Bayes model on the SMS Spam dataset
- Classifies new messages as either **Spam** or **Not Spam**
- Interactive web interface built with Streamlit

## 🧠 Tech Stack

- Python
- Scikit-learn
- NLTK
- Pandas
- Streamlit

## 📁 Dataset

- [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) from UCI / Kaggle

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/spam-email-detector.git
    cd spam-email-detector
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## 🎯 Future Improvements

- Save and load model using `joblib`
- Add word cloud or data visualizations
- Deploy to Streamlit Cloud or HuggingFace Spaces

---

## 🛡️ License

This project is open-source under the [MIT License](LICENSE).

