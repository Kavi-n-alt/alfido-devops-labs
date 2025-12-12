# devops-labs


# Task1 — Dockerize Flask App

## Steps to run locally (Codespaces / WSL)
1. Build & start:
   docker-compose build
   docker-compose up -d
2. Check container:
   docker ps
3. Test endpoint:
   curl http://localhost:5000/
   or open browser: http://localhost:5000

## Files
- app.py
- requirements.txt
- Dockerfile (multi-stage)
- docker-compose.yml
