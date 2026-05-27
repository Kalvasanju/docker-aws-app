# Docker AWS EC2 Deployment Project

## Project Overview
This project demonstrates containerization using Docker and deployment on AWS EC2.

## Technologies Used
- Python Flask
- Docker
- AWS EC2
- GitHub
- Ubuntu Linux

## Project Files
- app.py
- Dockerfile
- requirements.txt

## Steps Performed
1. Created Flask application
2. Created Dockerfile
3. Built Docker image
4. Pushed code to GitHub
5. Launched AWS EC2 instance
6. Installed Docker on EC2
7. Cloned GitHub repository
8. Built Docker image on EC2
9. Ran Docker container
10. Hosted application publicly

## Public Application URL
http://54.252.173.159:5000

## Docker Command Used

### Build Image
```bash
sudo docker build -t docker-aws-app .
```

### Run Container
```bash
sudo docker run -d -p 5000:5000 --name flask-app docker-aws-app
```