# Simple Python Docker App

A minimal Python Flask app, containerized using Docker.  
Great for learning the basics of web development and containerization.

## 🔧 Features

- Lightweight Flask web server
- Simple REST API returning JSON
- Fully Dockerized
- Clean and easy to understand structure

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mkazemi1985/simple-python-docker-app.git
cd simple-python-docker-app

### 2. Build the Docker image

docker build -t simple-python-app .

### 3. Run the Docker container

docker run -p 5000:5000 simple-python-app

Then open your browser and go to:

http://localhost:5000/

You should see:

{"message": "Hello from a simple Python Flask app! 🚀"}

## 🧱 Project Structure

simple-python-docker-app/
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md

## 📦 Tech Stack

Python 3.10

Flask

Docker
