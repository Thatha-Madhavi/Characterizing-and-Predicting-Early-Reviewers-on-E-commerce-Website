# Characterizing-and-Predicting-Early-Reviewers-on-E-commerce-Website

A Java-based system to analyze product reviews, identify early reviewers, and support effective product marketing on e-commerce platforms.

## 📌 Overview

Early reviewers play a critical role in e-commerce platforms, as customers rely heavily on early product feedback to make purchase decisions.
This project analyzes reviewer behavior, classifies review sentiments, and predicts which users are likely to become early reviewers.

The entire system is built using Java, includes Naïve Bayes–based sentiment analysis, and provides an admin dashboard with charts and insights for marketing purposes.

## ✨ Features

✔ Developed using Java, JSP, Servlets, and MySQL
✔ Identifies “early reviewers” using time-based product lifecycle stages
✔ Sentiment classification using Naïve Bayes Algorithm
✔ Analyzes user rating behavior & review patterns
✔ Provides visual insights using Bar, Pie, and Line charts
✔ User module for browsing products & submitting reviews
✔ Admin module for managing products & analyzing sentiments

## 🧠 System Workflow
### 1️⃣ User Module

- Register/Login

- Browse products

- Submit review + rating

- System evaluates sentiment

- Review stage stored for early-reviewer detection

### 2️⃣ Admin Module

- Upload/manage products

- View all user reviews

- Analyze sentiment (Positive/Negative/Neutral)

- Identify early reviewers

- Visualize results using charts

## 🧪 Technology Stack

- Frontend: JSP, HTML, CSS
- Backend: Java (Servlets, Core Java), Naïve Bayes Algorithm
- Database: MySQL
- Server: Apache Tomcat
- IDE: NetBeans / Eclipse
- Charts: JFreeChart / Chart Libraries

## 📂 Project Structure
Characterizing-and-Predicting-Early-Reviewers/
│

├── src/
│   ├── controller/        # Java Servlets (login, reviews, admin)
│   ├── model/             # Java classes (User, Product, Review, Sentiment, Prediction)
│   ├── dao/               # Database operations (MySQL)
│   ├── utils/             # DB connection & helper functions
│   └── ...                # Other Java files
│

├── WebContent/
│   ├── user/              # User JSP pages
│   ├── admin/             # Admin JSP pages (charts, analysis)
│   ├── assets/            # CSS, JS, images
│   ├── index.jsp
│   ├── login.jsp
│   └── register.jsp
│

├── database/
│   └── ecomm_reviews.sql  # MySQL database file
│

├── charts/                # Generated charts (pie, bar, line)
│

├── documentation/
│   └── Project_Report.pdf
│

├── config/
│   └── db.properties      # DB credentials
│

└── README.md


## 📊 Machine Learning Component
### Naïve Bayes Sentiment Analysis

Used for classifying review text into:

- Positive

- Neutral

- Negative

This helps in understanding reviewer impact and predicting early reviewer behavior.

## 🚀 How to Run the Project
### Prerequisites

- JDK 8 or above

- MySQL installed

- Apache Tomcat server configured

- NetBeans or Eclipse IDE

### Steps

- Clone the repository

- Import the Java project into NetBeans/Eclipse

- Create a MySQL database and import ecomm_reviews.sql

- Update database credentials in your Java config file

- Run the project using Apache Tomcat

**Open in browser:**

http://localhost:8080/EarlyReviewerSystem/

## 🔮 Future Enhancements

- Integrate ML libraries like Weka for advanced classification

- Add deep learning (BERT/BiLSTM) for improved sentiment accuracy

- Build an interactive admin dashboard

- Add real-time reviewer trend graphs

- Implement product recommendation engine

## 📌 Note

A few project files are missing — I will upload them soon.

## 🧑‍💻 Author

Madhavi Thatha

## 📜 License

MIT License
