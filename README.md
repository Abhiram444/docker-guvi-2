echo "# Docker Task 2

## Project Overview
This project demonstrates deployment of a simple website using Docker and Docker Compose on AWS EC2.

## Technologies Used
- AWS EC2 (Amazon Linux 2)
- Docker
- Docker Compose
- Nginx

## Project Structure
- Dockerfile
- docker-compose.yml
- index.html
- README.md

## How It Works
The Dockerfile uses the official Nginx image and copies the index.html file into the default Nginx web directory.  
Docker Compose builds the image and runs the container by exposing port 80.

## How to Run

### Build and Start
docker-compose up --build -d

### Check Running Containers
docker ps

### Access Website
Open: http://<EC2-Public-IP>

## Author
Abhiram

" > README.md
