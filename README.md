# React + FastAPI + PostgreSQL CRUD

A simple full-stack CRUD application for managing products.

## Stack
- Frontend: React + Vite
- Backend: FastAPI + SQLAlchemy
- Database: PostgreSQL
- Deployment: Docker + Docker Compose

## Run
1. Install Docker Desktop.
2. From this directory run:
   `docker compose up --build`
3. Open:
   - Frontend: http://localhost:5173
   - Backend API docs: http://localhost:8000/docs
   - API: http://localhost:8000/products

To stop:
`docker compose down`

To remove the database volume too:
`docker compose down -v`
