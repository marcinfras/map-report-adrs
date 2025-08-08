# 0001 – Initial Tech Stack

## Status
Accepted

## Context
I am developing a personal portfolio project called **map-report**, which allows users to report local issues in their city (e.g., potholes, broken street lights) via an interactive map interface.  
The project will demonstrate my skills in fullstack development, backend integration, geospatial data handling, and deployment to a production-like environment.

Core planned features:
- User authentication (standard login + Google OAuth)
- Interactive map with pins representing user reports
- File uploads (avatars, issue photos)
- Role-based access control (resident / administrator)
- Administrator tools for generating area-specific reports
- Queue-based email notifications to administration

My main goals in choosing the stack:
- Showcase strong fullstack development skills
- Implement modern, in-demand technologies used in production systems
- Build something deployable on cloud infrastructure (AWS)
- Work with tools that have strong community support and good documentation

## Decision
I decided to use:
- **Frontend:** React + TypeScript
- **Backend:** Express.js + TypeScript
- **Database:** MongoDB with Mongoose ODM
- **Deployment:** AWS EC2 + ECR with Docker and Portainer

This selection balances flexibility, performance, and my personal learning objectives, while also keeping the stack relevant for potential employers reviewing my portfolio.

## Consequences
- **Positive:**
  - Demonstrates ability to build and connect a modern fullstack application.
  - MongoDB’s geospatial features are well-suited for map-related data.
  - Dockerized architecture ensures smooth local and cloud deployment.
  - Shows proficiency in applying best practices across both frontend and backend.

- **Negative:**
  - Express.js requires more boilerplate compared to frameworks like NestJS.
  - MongoDB may require additional aggregation logic for more complex queries.
