# 📶 Telecom System (Spring Boot + Redis)

## 🚀 Features
- JWT Authentication
- Redis Caching
- Rate Limiting
- Real-time Data Usage Tracking
- Token Blacklisting (Logout)
- Recharge System

## 🧠 Redis Use Cases
- Cache plans
- Store user sessions
- Rate limiting
- Data usage tracking
- Token blacklist

## ⚙️ Tech Stack
- Spring Boot
- Spring Security
- Redis
- MySQL

## APIs

### Login
POST /auth/login?mobile=9999999999

### Recharge
POST /recharge?userId=1&planId=101

### Consume Data
POST /consume?userId=1&mb=100

### Check Usage
GET /usage?userId=1


This project demonstrates how Redis can be used in real-world telecom systems for high-performance and scalability.
