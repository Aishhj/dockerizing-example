# Dockerizing Example - Flask App

This is a simple Python Flask application that runs inside a Docker container.

## 🚀 Features
- Flask web app returning a simple "Hello" message
- Dockerized for easy deployment
- Exposes port **5000** by default

---

## 📂 Project Structure
dockerizing-example/
│-- app.py
│-- requirements.txt
│-- Dockerfile
└-- README.md

## 🛠 How to Run Locally (Without Docker)
pip install -r requirements.txt \\
python app.py \\
The app will run on http://localhost:5000.

## 🐳 How to Run with Docker
Build the image\\
docker build -t dockerizing-example:v2 .

Run the container \\
docker run -p 5000:5000 dockerizing-example:v1


Edit
er run -p 5000:5000 dockerizing-example:v1
Open http://localhost:5000 in your browser.
