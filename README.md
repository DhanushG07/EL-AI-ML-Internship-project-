# EL-AI-ML-Internship-project-
# AI Virtual Career Counsellor  
### Career Prediction Based on Skills and Interests

> An intelligent ML-powered chatbot that recommends ideal career paths based on a user's skills and interests.

## Overview

This project builds an **AI-powered virtual career counsellor** that analyzes users’ skills and interests to recommend suitable career options using Natural Language Processing (NLP) and Machine Learning. The system is trained on real-world data and deployed via a Streamlit chatbot interface for real-time use.

## Project Structure
AI_Virtual_Career_Counsellor/
│
├── data/   
│ └── AI-based Career Recommendation System.csv     
│         
├── models/       
│ ├── career_model.pkl      
│ ├── cv.pkl     
│ └── label_encoder.pkl      
│        
├── app.py # Streamlit chatbot UI       
├── notebook.ipynb # Colab training notebook        
├── report.pdf # Final project report       
└── README.md # GitHub cover page      


##  Technologies Used

- Python 3
- Pandas
- Scikit-learn
- CountVectorizer
- LabelEncoder
- Naive Bayes Classifier
- Streamlit (for UI)
- [Google Colab](https://colab.research.google.com/drive/1A48wgk3vSnNxJWM1fTZBtDdQ1VriscuO?usp=sharing)

## How It Works

1. User enters their **skills** and **interests**
2. Input is vectorized using `CountVectorizer`
3. A **Naive Bayes** model predicts the best-fit career
4. Output is shown via a simple **chat-style UI** in Streamlit

## Sample Prediction

> **Input:**  
`Skills: Python, Excel`  
`Interests: Problem Solving, Technology`

> **Output:**  
🔮 Recommended Career: **Data Analyst**

## 📄 Project Report

The final project summary is available here: [`report.pdf`](./report.pdf)


## 👨‍💻 Author

- **Dhanush G**  
  BBA Student | Aspiring Data Scientist  
  📧 dhanushg0710@gmail.com  
  🔗 [LinkedIn](https://www.linkedin.com/in/dhanush-g-805492345)


## 🔗 Deployment (Optional)
- [Google Colab Notebook]
