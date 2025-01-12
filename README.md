# 📰 News App

The **News App** is a full-stack application that allows users to browse categorized news articles in real-time. Built with a modern, scalable, and modular architecture, this app integrates a Spring Boot backend with a dynamic frontend to provide seamless user experience and robust API capabilities.

Check out the hosted app on AWS: http://3.73.84.1/

---

## 📋 Features

### Frontend:
- Dynamic and responsive user interface built with Angular.
- Filters to search news by:
  - **Category** (e.g., Technology, Sports, Politics, etc.).
  - **Author**, and **Publication Date**.
- Pagination to handle large data sets efficiently.
- Sort options (by date).

### Backend:
- Spring Boot-powered RESTful API to handle news data.
- Implements robust filtering, sorting, and pagination features.
- CORS-enabled for seamless communication with the frontend.
- Modular service layer for easy maintenance and extension.

### Database:
- MongoDB
- Stores articles with metadata (e.g., title, author, date) in two collections: uncategorized- and categorzed-articles
- Efficient querying for search and filters.

### Infrastructure:
- Hosted on AWS for scalability and reliability.
- Configurable environments: TBD

---

## 🛠️ Technology Stack

### Frontend:
- **Framework**: Angular
- **Styling**: CSS/Bootstrap

### Backend:
- **Framework**: Spring Boot
- **Language**: Java
- **Build Tool**: Maven
- **REST API**: RESTful services with JSON responses

### Database:
- **Type**: MongoDB

### Infrastructure:
- **Hosting**: AWS EC2 for backend as well as frontend.
- **Containerization**: Docker.
- **Monitoring**: TBD

---
