# 📰 News App

The **News App** is a full-stack application that allows users to browse news articles in real-time. Built with a modern, scalable, and modular architecture, this app uses NewsAPI as a source of news, stores and categorizes articles using a trained Bert classifier. This provides seamless user experience and robust API capabilities.

Check out the hosted app on AWS: http://3.73.84.1/

---

## 📋 Features

### Frontend:
- Dynamic and responsive user interface built with Angular
- Filters to search news by:
  - **Category** (e.g., Technology, Sports, Politics, etc.).
  - **Author**, and **Publication Date**.
- Pagination to handle large data sets efficiently
- Sort options (by date).
- Source code: https://github.com/ferasalnaem/news-app

### Backend services:
* #### News-Aggregator:
  - Spring Boot-powered RESTful API to handle news data
  - Fetches uncategorized articles from NewsAPI and stores it in DB
  - Provides endpoint to retrieve categorized articles to be displayed on the frontend
  - Implements robust filtering, sorting, and pagination features
  - Source code: https://github.com/ferasalnaem/news-aggregator
    
* #### News-Categorizer-API:
  - Flask API for categorising articles
  - Reads uncategoriezd articles, uses Bert classifier to categorise articles and stores it
  - Source code: https://github.com/ferasalnaem/news-categorizer-api
    
### Training News-Categorizer:
- Using News Category Dataset: https://www.kaggle.com/datasets/rmisra/news-category-dataset
- Includes data preprocessing and fine tuning bert model 
- Source code: https://github.com/ferasalnaem/news-categorizer-training
 
### Database:
- MongoDB
- Stores articles with metadata (e.g., title, author, date) in two collections: uncategorized- and categorzed-articles
- Efficient querying for search and filters

### Infrastructure:
- **Hosting**: AWS EC2 for backend as well as frontend
- **Containerization**: Docker
- Configurable environments: TBD

---
