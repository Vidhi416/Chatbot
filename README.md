# AI-Powered Job Recommendation Chatbot

## Overview

This project is an AI-powered Job Recommendation Chatbot that analyzes a candidate's skills, qualifications, and experience level to suggest suitable career paths. The system combines intent-based conversational capabilities with a machine learning model that predicts the most relevant job role based on user input.

Unlike traditional chatbots that rely solely on predefined responses, this chatbot utilizes an Artificial Neural Network (ANN) trained on candidate profiles to generate personalized job recommendations.

---

## Features

* Conversational chatbot interface
* Intent recognition (Greetings, Help, Thanks, Goodbye)
* Job role recommendation based on user profile
* Skill extraction and vectorization
* Qualification and experience-level encoding
* ANN-based multi-class classification
* Top-3 job role suggestions with confidence scores
* Early stopping and regularization to prevent overfitting

---

## Tech Stack

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy

---

## Machine Learning Pipeline

1. Data preprocessing and cleaning
2. Skill extraction and binary vectorization
3. Qualification encoding using Label Encoding and One-Hot Encoding
4. Experience level encoding
5. Feature concatenation
6. ANN model training and evaluation
7. Job role prediction and recommendation

---

## Model Architecture

Input Layer
↓
Dense Layer (128 Neurons, ReLU)
↓
Batch Normalization
↓
Dropout (0.3)
↓
Dense Layer (64 Neurons, ReLU)
↓
Batch Normalization
↓
Dropout (0.2)
↓
Output Layer (Softmax)

The model uses:

* ReLU activation
* Batch Normalization
* Dropout Regularization
* Adam Optimizer
* Early Stopping

---

## How It Works

The user enters:

* Skills
* Qualification
* Experience Level (Junior/Mid/Senior)

The chatbot extracts relevant information, converts it into machine-learning features, and predicts the most suitable job role. It also displays the top three recommended career options along with prediction confidence scores.

---

## Future Enhancements

* Integration with Large Language Models (LLMs)
* Resume parsing and automated skill extraction
* Web-based interface using Flask/Django
* Real-time job recommendation APIs
* Integration with job portals and recruitment platforms

---

## Applications

* Career guidance systems
* Recruitment support tools
* Educational counseling platforms
* HR screening assistance

## Author

Vidhi Agrawal
