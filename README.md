# Cloud Project _ Aden & Fatima

##  Project Overview
A cloud-native MERN stack web application deployed using modern AWS infrastructure.  
Backend is deployed on EC2 using Docker.  
Frontend is deployed using Elastic Beanstalk.

##  Features
- User Authentication (JWT-based)
- CRUD operations on Posts
- File/Image Upload using AWS S3
- Database hosted on Amazon RDS (MySQL)

##  Technologies Used
- React (Frontend)
- Node.js + Express (Backend)
- MySQL (via Amazon RDS)
- AWS EC2 (Dockerized backend)
- AWS Elastic Beanstalk (Frontend)
- AWS S3 (Image/file upload)
- AWS IAM (Security and access policies)

##  Live Demo Links 
- Frontend URL: [Frontend Link]()
- Backend URL: [Backend Link]()

##  Deployment Guide (Short)
```bash
# Clone the repo
git clone https://github.com/adenamar03/cloud_project_aden_fatima.git
cd cloud_project_aden_fatima

# Start services with Docker
docker-compose up -d
