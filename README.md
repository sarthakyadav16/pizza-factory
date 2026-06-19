# 🍕 Pizza Factory - Dockerized Web App

![Pizza Banner](https://img.shields.io/badge/Project-Pizza%20Factory-orange?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-Enabled-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Running-success?style=for-the-badge)

---

## 🚀 Project Overview

**Pizza Factory** is a simple and interactive frontend web application where users can view and order different types of pizzas 🍕.

This project demonstrates:

* 🌐 Frontend development using HTML & CSS
* 🐳 Containerization using Docker
* ⚡ Deployment using Nginx

---

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript
* Docker
* Nginx

---

## 📂 Project Structure

```
pizza-factory/
│── index.html
│── style.css
│── app.js
│── Dockerfile
│
├── images/
│   ├── margherita.jpg
│   ├── pepperoni.jpg
│   ├── veggie.jpg
│
└── screenshots/
    └── output.png
```

---

## ▶️ How to Run the Project

### 🔹 Step 1: Clone Repository

```
git clone https://github.com/your-username/pizza-factory.git
cd pizza-factory
```

---

### 🔹 Step 2: Build Docker Image

```
docker build -t pizza-frontend .
```

---

### 🔹 Step 3: Run Container

```
docker run -d -p 8080:80 pizza-frontend
```

---

### 🔹 Step 4: Open in Browser

```
http://localhost:8080
```

---

## ✨ Features

* 🍕 Multiple pizza options
* 🎨 Clean UI design
* ⚡ Fast loading with Nginx
* 🐳 Dockerized for easy deployment

---

## 📌 Future Improvements

* 🛒 Add cart functionality
* 🔐 User login system
* 🌐 Backend integration (Node.js)
* ☁️ Deploy on AWS / Kubernetes

---

## 👨‍💻 Author

**Sarthak Yadav**

---

## ⭐ Support

If you like this project:

* ⭐ Star this repository
* 🍴 Fork it
* 📢 Share with others

---

## 💡 Learnings

This project helped in understanding:

* Docker containerization
* Web app deployment
* Project structuring for real-world applications

---

🔥 *Made with passion for learning DevOps & Web Development*
