# Fake Job Detection Using Python

## 📌 Project Overview

This project is an AI-based Fake Job Detection System developed using Python and Machine Learning.

The system analyzes job descriptions and predicts whether a job posting is **Likely Genuine** or **Potentially Fake**. It also provides a model confidence score and highlights some common risk indicators.

## 🎯 Objectives

- Detect potentially fake job postings.
- Use Natural Language Processing (NLP) to analyze job descriptions.
- Apply Machine Learning classification algorithms.
- Compare different Machine Learning models.
- Provide a confidence score for predictions.
- Identify common warning signs in job descriptions.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Gradio
- Google Colab

## 🤖 Machine Learning Models

The following models were used and compared:

- Logistic Regression
- Random Forest
- Naive Bayes

TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert text into numerical features for Machine Learning.

## 📊 Project Workflow

1. Load the job posting dataset.
2. Select a sample of real and fake job postings.
3. Handle missing values.
4. Combine important text fields.
5. Clean the text data.
6. Convert text into numerical features using TF-IDF.
7. Train Machine Learning models.
8. Compare model performance.
9. Select the best-performing model.
10. Predict whether a new job posting is genuine or potentially fake.
11. Display the result through a simple Gradio interface.

## 🔍 Output

The system provides:

- Job classification
- Model confidence score
- Basic risk indicators
- Machine Learning model performance comparison
- Confusion matrix

## 📁 Project Files

```text
Fake-job-detection-project/
│
├── Fake_Job_Detection.ipynb
└── README.md
```

## ⚠️ Limitations

This project uses a small sample dataset for educational purposes. Therefore, the results may not represent the performance of a real-world fake job detection system.

The system should be used as a supporting tool and not as the only method for deciding whether a job is genuine.

## 👩‍💻 Author

Created as a first-year BTech Machine Learning project using Python.
