# fake-news-detector

[Live Run ✈️](https://fake-news-detector-ppavbqxoke7yv5fxuzrtwa.streamlit.app/)


# 🧠 Fake News Detection System

A machine learning-powered web application built with Streamlit to classify news articles as **Real** or **Fake**. This project leverages Natural Language Processing (NLP) techniques to preprocess text data and a Logistic Regression model to perform the classification, achieving an accuracy of over 98%.



---

## ✨ Features

-   **Interactive Web App**: A clean and user-friendly interface built with Streamlit for real-time predictions.
-   **High-Performance Model**: Utilizes a fine-tuned Logistic Regression classifier that achieves **98% accuracy**.
-   **Advanced NLP Pipeline**: Implements a robust text preprocessing pipeline including cleaning, tokenization, stop-word removal, and lemmatization using NLTK.
-   **Efficient Feature Extraction**: Uses `TfidfVectorizer` to convert text into meaningful numerical features.
-   **Detailed Performance Metrics**: The model's effectiveness is validated with metrics like Precision, Recall, F1-Score, a Confusion Matrix, and ROC Curve analysis.

---

## 🛠️ Tech Stack

-   **Backend & ML**: Python, Scikit-learn, NLTK, Pandas
-   **Web Framework**: Streamlit
-   **Model Persistence**: Joblib
-   **Data Visualization**: Matplotlib, Seaborn

---

## 📊 Dataset

The model was trained on the "Fake and Real News" dataset, which contains thousands of articles labeled as either real or fake.

-   **`True.csv`**: Contains real news articles.
-   **`Fake.csv`**: Contains fake news articles.

Each article is preprocessed and assigned a label:
-   **`1`**: Real News ✅
-   **`0`**: Fake News ❌

---

## 🚀 Getting Started

Follow these steps to set up and run the project on your local machine.

### Prerequisites

-   Python 3.8 or higher
-   `pip` package manager

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/fake-news-detector.git](https://github.com/your-username/fake-news-detector.git)
    cd fake-news-detector
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Download NLTK resources:**
    The application will automatically download the necessary NLTK data (`punkt`, `stopwords`, `wordnet`) on its first run.

### Running the App

1.  **Start the Streamlit application:**
    ```bash
    streamlit run app.py
    ```
2.  Open your web browser and navigate to `http://localhost:8501`.

---

## 📈 Model Performance

The Logistic Regression model demonstrates excellent performance in distinguishing between real and fake news.

-   **Accuracy**: **98.6%**
-   **Classification Report**:
    | Class | Precision | Recall | F1-Score |
    | :---: | :-------: | :----: | :------: |
    | Fake  |   0.99    |  0.98  |   0.99   |
    | Real  |   0.98    |  0.99  |   0.99   |

-   **Confusion Matrix**: The model shows a high number of true positives and true negatives, with very few misclassifications.
-   **ROC AUC Score**: The Area Under the Curve is **0.99**, indicating outstanding discriminatory power.

---

## 📧 Contact

For any questions, feedback, or collaboration inquiries, please feel free to reach out.

-   **Author**: [Shivesh Kumar]
-   **Email**: [shiveshkumar73520gmail.com]
-   **GitHub**: [@Alphashivesh](https://github.com/alphashivesh)
