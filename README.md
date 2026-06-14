#Title: MACHINE LEARNING MODEL IMPLEMENTATION

#Subtitle: Intelligent Spam Detection System Using Natural Language Processing and Machine Learning

#Name: Ankush Dhanokar

#Intern ID: CTIS9672

#Company: Codtech IT Solutions

#Domain: Python Programming

#Duration: 12 Weeks

#Mentor: Neela Santosh

#OutPut:  <img width="800" height="407" alt="Image" src="https://github.com/user-attachments/assets/e2b89fd8-aa26-4d0c-8913-d2ea57028a26" />


# 📧 Spam Email Detection Using Machine Learning

## Internship Task - 4: Machine Learning Model Implementation

### Project Overview

This project implements a Spam Email Detection System using Machine Learning and Natural Language Processing (NLP). The model is trained to classify messages as either **Spam** or **Ham (Not Spam)** using the Multinomial Naive Bayes algorithm and TF-IDF Vectorization.

---

## Objective

The objective of this project is to develop a predictive machine learning model using Scikit-Learn that can automatically identify spam messages from a dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Machine Learning Algorithm

**Multinomial Naive Bayes**

This algorithm is widely used for text classification problems such as spam detection because of its simplicity, speed, and effectiveness.

---

## Project Workflow

1. Dataset Loading
2. Data Exploration
3. Data Preprocessing
4. Train-Test Split
5. TF-IDF Feature Extraction
6. Model Training
7. Model Evaluation
8. Spam Prediction

---

## Dataset Information

* Dataset Type: SMS/Email Spam Detection Dataset
* Total Messages: 145
* Features:

  * Label (Spam/Ham)
  * Message Text

---

## Model Evaluation

| Metric           | Value  |
| ---------------- | ------ |
| Training Samples | 116    |
| Testing Samples  | 29     |
| Accuracy         | 82.76% |

---

## Sample Predictions

| Message                                                | Prediction |
| ------------------------------------------------------ | ---------- |
| Congratulations! You have won ₹50,000. Click here now! | Spam       |
| Hey bro, are you coming to college today?              | Ham        |
| Your account has been suspended. Click here to verify. | Spam       |

---

## Results

The machine learning model successfully classifies messages as Spam or Ham using TF-IDF feature extraction and the Multinomial Naive Bayes algorithm. The model achieved an accuracy of approximately **82.76%** on the test dataset.

---

## Future Improvements

* Increase dataset size for better accuracy.
* Compare multiple machine learning algorithms.
* Deploy the model using Streamlit or Flask.
* Add real-time email classification functionality.

---

## Repository Structure

```text
spam-email-detection-ml/
│
├── spam_email_detection.ipynb
├── README.md
└── spam.csv

```

** Internship Project Submitted for **CodTech IT Solutions**

---

## License

This project is created for educational and internship purposes.


