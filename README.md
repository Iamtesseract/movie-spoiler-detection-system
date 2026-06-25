# Movie Spoiler Detection System

Overview

The Movie Spoiler Detection System is a Natural Language Processing (NLP) and Machine Learning project developed to automatically identify whether a movie review contains spoilers.

Online reviews frequently reveal critical plot details that can diminish the viewing experience for other users. This project addresses this issue by classifying reviews as either Spoiler or Non-Spoiler using machine learning techniques.

The system employs text preprocessing, TF-IDF feature extraction, and classification algorithms such as Support Vector Machine (SVM) and Multinomial Naive Bayes.

---

Objectives

- Detect spoiler-containing movie reviews automatically.
- Apply Natural Language Processing techniques to textual data.
- Compare machine learning algorithms for text classification.
- Improve user experience by reducing exposure to spoilers.

---

Features

- Movie review classification
- Spoiler and non-spoiler prediction
- Text preprocessing using NLTK
- Stopword removal
- TF-IDF feature extraction
- Support Vector Machine (SVM) classifier
- Multinomial Naive Bayes classifier
- Performance evaluation using standard metrics
- Model persistence using Joblib

---

Technologies Used

Technology| Purpose
Python| Programming Language
Pandas| Data Processing
NLTK| Natural Language Processing
Scikit-learn| Machine Learning
TF-IDF| Feature Extraction
Support Vector Machine| Classification
Naive Bayes| Classification
Joblib| Model Serialization

---

Dataset

The project utilizes the IMDb Spoiler Dataset.

The dataset contains:

- Movie reviews
- Plot summaries
- Plot synopses
- Spoiler labels

Target Variable

Label| Description
1| Spoiler
0| Non-Spoiler

---

System Workflow

IMDb Dataset
      │
      ▼
Data Loading
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Extraction (TF-IDF)
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Classification
      │
      ▼
Performance Evaluation
      │
      ▼
Model Saving

---

Methodology

1. Data Collection

Movie reviews and movie metadata are loaded from the IMDb Spoiler Dataset.

Files used:

- IMDB_reviews.json
- IMDB_movie_details.json

2. Data Integration

Movie reviews are merged with movie metadata using the "movie_id" field. This enriches the review data with additional contextual information such as plot summaries and plot synopses.

3. Text Preprocessing

The following preprocessing steps are applied:

- Conversion to lowercase
- Removal of punctuation
- Tokenization
- Stopword removal

These steps reduce noise and improve model performance.

4. Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert textual data into numerical feature vectors suitable for machine learning algorithms.

5. Model Training

Support Vector Machine (SVM)

SVM is used to identify an optimal decision boundary between spoiler and non-spoiler reviews.

Key advantages:

- Effective for high-dimensional text data
- Strong classification performance
- Good generalization capability

Multinomial Naive Bayes

Naive Bayes is a probabilistic classifier commonly used in text classification.

Key advantages:

- Fast training and prediction
- Computationally efficient
- Well-suited for NLP tasks

---

Performance Evaluation

The models are evaluated using the following metrics:

Accuracy

Measures the overall proportion of correctly classified reviews.

Precision

Measures how many reviews predicted as spoilers are actually spoilers.

Recall

Measures how many actual spoiler reviews are successfully identified.

F1 Score

Provides a balance between precision and recall.

Classification Report

Generated using Scikit-learn's "classification_report()" function and includes:

- Precision
- Recall
- F1 Score
- Support

---

Model Persistence

The trained models and vectorizer are saved using Joblib.

Generated files:

svm_spoiler_model.pkl
nb_spoiler_model.pkl
tfidf_vectorizer.pkl

These files enable future deployment without retraining the models.

---

Project Structure

movie-spoiler-detection-system/
│
├── README.md
├── spoiler_detection.py
├── requirements.txt
├── svm_spoiler_model.pkl
├── nb_spoiler_model.pkl
├── tfidf_vectorizer.pkl
└── screenshots/

---

Installation

Clone the repository:

git clone https://github.com/yourusername/movie-spoiler-detection-system.git

Navigate to the project directory:

cd movie-spoiler-detection-system

Install dependencies:

pip install -r requirements.txt

---

Running the Project

Execute the following command:

python spoiler_detection.py

The application will:

1. Load the dataset
2. Preprocess textual data
3. Extract TF-IDF features
4. Train machine learning models
5. Evaluate model performance
6. Save trained models

---

Future Enhancements

- Deep Learning-based spoiler detection
- Long Short-Term Memory (LSTM) networks
- Transformer-based models such as BERT
- Web application deployment
- Browser extension for spoiler filtering
- Mobile application integration
- Multilingual spoiler detection

---

Learning Outcomes

This project provided practical experience in:

- Natural Language Processing
- Text Classification
- Machine Learning
- Data Preprocessing
- Feature Engineering
- Model Evaluation
- Python Programming
- Dataset Handling

---

Author

Sathyapriya P R

Electronics and Communication Engineering

Areas of Interest:

- Artificial Intelligence
- Machine Learning
- Embedded Systems
- Internet of Things (IoT)
- Data Analytics

---

License

This project is intended for educational and research purposes.Movie Spoiler Detection System

Overview

The Movie Spoiler Detection System is a Natural Language Processing (NLP) and Machine Learning project developed to automatically identify whether a movie review contains spoilers.

Online reviews frequently reveal critical plot details that can diminish the viewing experience for other users. This project addresses this issue by classifying reviews as either Spoiler or Non-Spoiler using machine learning techniques.

The system employs text preprocessing, TF-IDF feature extraction, and classification algorithms such as Support Vector Machine (SVM) and Multinomial Naive Bayes.

---

Objectives

- Detect spoiler-containing movie reviews automatically.
- Apply Natural Language Processing techniques to textual data.
- Compare machine learning algorithms for text classification.
- Improve user experience by reducing exposure to spoilers.

1. Data Collection


Generated using Scikit-learn's "classification_report()" function and includes:

- Precision
- Recall
- F1 Score
- Support

---

Model Persistence

The trained models and vectorizer are saved using Joblib.

Generated files:

svm_spoiler_model.pkl
nb_spoiler_model.pkl
tfidf_vectorizer.pkl

These files enable future deployment without retraining the models.

---

Project Structure

movie-spoiler-detection-system/
│
├── README.md
├── spoiler_detection.py
├── requirements.txt
├── svm_spoiler_model.pkl
├── nb_spoiler_model.pkl
├── tfidf_vectorizer.pkl
└── screenshots/

---

Installation

Clone the repository:

git clone https://github.com/yourusername/movie-spoiler-detection-system.git

Navigate to the project directory:

cd movie-spoiler-detection-system

Install dependencies:

pip install -r requirements.txt

---

## Results

The trained models were evaluated using Accuracy, Precision, Recall, and F1-Score.

Example output:

SVM Accuracy: XX%

Naive Bayes Accuracy: XX%

Detailed classification reports are generated for both models.

Running the Project

Execute the following command:

python spoiler_detection.py

The application will:

1. Load the dataset
2. Preprocess textual data
3. Extract TF-IDF features
4. Train machine learning models
5. Evaluate model performance
6. Save trained models

---

Future Enhancements

- Deep Learning-based spoiler detection
- Long Short-Term Memory (LSTM) networks
- Transformer-based models such as BERT
- Web application deployment
- Browser extension for spoiler filtering
- Mobile application integration
- Multilingual spoiler detection

---

Learning Outcomes

This project provided practical experience in:

- Natural Language Processing
- Text Classification
- Machine Learning
- Data Preprocessing
- Feature Engineering
- Model Evaluation
- Python Programming
- Dataset Handling

---

Author

Sathya

Electronics and Communication Engineering

Areas of Interest:

- Artificial Intelligence
- Machine Learning
- Embedded Systems
- Internet of Things (IoT)
- Data Analytics

---

License

This project is intended for educational and research purposes.e-spoiler-detection-system
Movie Spoiler Detection using NLP, TF-IDF, SVM and Naive Bayes
