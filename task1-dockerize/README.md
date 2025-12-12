# Task 1 – Dockerize a Simple Flask App

For this task, I created a simple Flask application and containerized it using Docker and docker-compose.  
The app exposes a single `/` endpoint that returns a JSON message.

## Files
- app.py – flask application
- requirements.txt – dependencies
- Dockerfile – container instructions
- docker-compose.yml – run configuration

## Commands I used
### Build the image
docker-compose build

### Start the container
docker-compose up -d

### Check running containers
docker ps

### Test the endpoint
curl http://localhost:5000/

Expected output:
{ "message": "Hello from Dockerized Flask App!" }

## What I learned
- How Docker builds images using a Dockerfile
- How docker-compose simplifies running containers
- How to expose ports and test endpoints

