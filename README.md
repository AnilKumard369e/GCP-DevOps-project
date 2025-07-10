# Simple Python Flask App 🚀

This is a minimal Flask app to demonstrate how to containerize a Python application using Docker.

## 🛠 How to Run:

### Clone the repo:

```bash
git clone https://github.com/your-username/python-flask-app.git
cd python-flask-app
```

### Build the Docker Image

```bash
docker build -t flask-app .
```

### Run the Container

```bash
docker run -d -p 5000:5000 flask-app
```

### Test the App

Open your browser or curl:
```
http://localhost:5000
```

## 📂 Files

- `app.py`: Main application code
- `requirements.txt`: Python dependencies
- `Dockerfile`: Docker build instructions
- `.dockerignore`: Files ignored by Docker
- `.gitignore`: Files ignored by Git
