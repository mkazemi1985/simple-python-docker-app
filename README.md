# 🚀 Simple Python Docker App

A minimal Python Flask app, containerized using Docker.  
Great for learning the basics of web development and containerization.

---

## 🔧 Features

- 🧩 Lightweight Flask web server  
- ⚙️ Simple REST API returning JSON  
- 🐳 Fully Dockerized  
- 🧼 Clean and easy-to-understand structure  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/mkazemi1985/simple-python-docker-app.git
cd simple-python-docker-app
2️⃣ Build the Docker Image
bash
Copy
Edit
docker build -t simple-python-app .
3️⃣ Run the Docker Container
bash
Copy
Edit
docker run -p 5000:5000 simple-python-app
Open your browser and go to:
👉 http://localhost:5000

You should see:

json
Copy
Edit
{"message": "Hello from a simple Python Flask app! 🚀"}
🧱 Project Structure
bash
Copy
Edit
simple-python-docker-app/
├── app.py            # Main Flask app
├── requirements.txt  # Python dependencies
├── Dockerfile        # Docker build instructions
└── README.md         # This file
📦 Tech Stack
🐍 Python 3.10

🔥 Flask

🐳 Docker


