# Introduction to Containerization with Docker

This project demonstrates the basics of containerization using Docker.  
A simple Node.js web application is containerized using a Dockerfile and run inside a Docker container.

---

## Project Objective

- Understand containerization concepts
- Learn how to create a Dockerfile
- Build a Docker image
- Run an application inside a container
- Understand Docker image layers and port mapping

---

## Technologies Used

- Node.js
- Express.js
- Docker

---

## Project Structure

docker-demo/
│
├── app.js
├── package.json
├── package-lock.json
└── Dockerfile

---

## Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/docker-demo.git
cd docker-demo
```
## Step 2: Build Docker Image
```
docker build -t docker-demo .
```
## Step 3: Run Docker Container
```
docker run -p 3000:3000 docker-demo
```
## Access Application
```
http://localhost:3000
```

## Output
<img width="958" height="210" alt="image" src="https://github.com/user-attachments/assets/cf20bd55-85b0-431a-86bc-cdaf83d7a50b" />
