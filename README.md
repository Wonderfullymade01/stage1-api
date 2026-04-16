# Stage 1 API - HNG DevOps

## 📌 Project Description
This is a simple FastAPI-based REST API built and deployed as part of the HNG Stage 1 DevOps task.  
It demonstrates basic API development, deployment on an Ubuntu server, and reverse proxy configuration using Nginx.

---

## 🚀 Live URL
https://fiyinfoluwafayomi.duckdns.org

---

## 📡 API Endpoints

### 1. GET /
Returns API status.

Response:
```json
{
  "message": "API is running"
}
```

### 2. GET /health
Returns system health status. 

Response: 
```json
{
  "message": "healthy"
}
```

### 3. GET /me

Returns user information.

Response:
```json
{
  "name": "Fayomi Fiyinfoluwa",
  "email": "oluwaseyifayomi01@gmail.com",
  "github": "https://github.com/Wonderfullymade01"
}
```
