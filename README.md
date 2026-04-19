# 🚀 Dockerized Node.js Application

**Project Overview**
This project demonstrates how to containerize a simple Node.js application using Docker and deploy it on a cloud server (AWS EC2).

**Tech Stack**
* Node.js
* Docker
* AWS EC2
* GitHub

 **Project Structure**

node-docker-app/
├── app.js
├── package.json
├── Dockerfile

 **Run Application Locally**

** Install dependencies**

npm install

**Start application**

node app.js

---

** Run Using Docker**

** Build Docker Images**

docker build -t node-docker-app .

** Run Docker Container**

docker run -d -p 3000:3000 --name node-container node-docker-app

---

 **Access Application **

Open in browser:
http://<EC2-PUBLIC-IP>:3000

---

 **Docker Commands**

 **Stop Container**

docker stop node-container

 **Start Container**

docker start node-container

**Remove Container**
docker rm -f node-container
---
 **Learning Outcomes**

* Containerization using Docker
* Deploying applications on AWS EC2
* Managing container lifecycle
* Using GitHub for version control
* Basic DevOps workflow
---
** Future Improvements**

* CI/CD using Jenkins
* Docker Hub integration
* Kubernetes deployment
* Nginx reverse proxy

**Author**
Harshal Darbhe
