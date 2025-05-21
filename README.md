# Movie-Recommendation-System

# 📊 Recommendation System with Apache Spark & ALS

This project aims to develop a recommendation system that runs on big data using **Apache Spark** and the **ALS (Alternating Least Squares)** algorithm. It analyzes user ratings for products and provides personalized recommendations.

The project includes the following stages:

- **Data preprocessing and cleaning**
- **Data visualization**
- **Model training and evaluation**

Different ALS parameters such as `rank`, `lambda`, and `number of iterations` were tested to determine the best-performing model. Evaluation was conducted using **MSE** and **RMSE** metrics.

In addition, **cosine similarity** was used to predict which users are most likely to enjoy a specific product.

## 👥 Team Work

This assignment was completed by a team of **four people**. Each team member selected **four different combinations** of `lambda` and `iteration` values, ran the ALS training on their own computer, and then we **gathered all results on a single machine** for comparison and evaluation.

I personally contributed to:

- **Data preprocessing**
- **Generating visualizations**
- **Testing various ALS parameters** (like all team members)

---

📌 Technologies used: PySpark, Pandas, Matplotlib, Scikit-learn


