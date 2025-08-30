# Flask App with Docker 🚀

A simple **Flask web application** that prints a message.  
This project is designed for learning DevOps step by step:  
1. Run Flask app locally  
2. Containerize the app with Docker  

---

## 🛠️ Requirements
- Python 3.x  
- pip (Python package manager)  
- Docker Desktop  

---

## ▶️ Run Locally (Without Docker)

1. Clone this repository:
   ```bash
   git clone https://github.com/mohdyusufali0532/flask-docker-app.git
   cd flask-docker-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Start the Flask app:
   ```bash
   python app.py
   ```

4. Open in browser:
   ```
   http://127.0.0.1:5000
   ```

5. You should see:
   ```
   Hello DevOps from Flask + Docker!
   ```

---

## 🐳 Run with Docker

1. Build the Docker image:
   ```bash
   docker build -t flask-docker-app .
   ```

2. Run the container:
   ```bash
   docker run -p 5000:5000 flask-docker-app
   ```

3. Open in browser:
   ```
   http://127.0.0.1:5000
   ```

✅ The same output will appear inside the Docker container.
