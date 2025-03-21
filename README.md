# Personalized Shopping Assistant (Retail AI)

## 📌 Overview
The **Personalized Shopping Assistant** is an AI-driven recommendation system designed to enhance the e-commerce shopping experience by providing hyper-personalized product suggestions. This project leverages machine learning techniques to segment customers, predict purchasing behaviors, and offer smart recommendations through a chatbot interface.

## 🚀 Motivation
E-commerce giants like Amazon and Walmart maximize sales through personalized recommendations. This project aims to replicate similar capabilities by integrating customer segmentation, recommendation algorithms, and an NLP-powered chatbot.

## 📂 Dataset
- **Source**: Kaggle’s Online Retail dataset
- **Description**: Contains transactional data of an online retail store, including customer IDs, product descriptions, and purchase histories.

## 🔥 Features
- **Customer Segmentation:** Uses K-means clustering to categorize shoppers based on purchasing behavior.
- **Hybrid Recommendation System:** Combines collaborative filtering and content-based filtering to enhance product recommendations.
- **NLP-Powered Chatbot:** Suggests fashion trends and product recommendations based on user queries.
- **Deployment:** A Flask-based API that predicts user purchase behaviors and serves recommendations dynamically.

## Screenshots
- UI 
![image](https://github.com/user-attachments/assets/cfa76ee7-75fa-4c01-827f-ce8448562b7b)


## 📌 Tech Stack
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn, TensorFlow/PyTorch
- **NLP & Chatbot:** NLTK, spaCy, OpenAI GPT
- **Backend & Deployment:** Flask, FastAPI, Docker

## 🛠️ Project Workflow
1. **Data Preprocessing:** Clean and transform the dataset for analysis.
2. **Customer Segmentation:** Apply K-means clustering to group users.
3. **Recommendation System:** 
   - **Collaborative Filtering:** Suggests items based on user similarity.
   - **Content-Based Filtering:** Suggests items similar to past purchases.
4. **NLP Chatbot:** 
   - Train an NLP model to suggest trending products.
   - Integrate with Flask API.
5. **Deployment:** Package the model and serve recommendations via API endpoints.

## 🏗️ Setup & Installation
```sh
# Clone the repository
git clone https://github.com/your-repo/personalized-shopping-assistant.git
cd personalized-shopping-assistant

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the Flask API
python app.py
```




