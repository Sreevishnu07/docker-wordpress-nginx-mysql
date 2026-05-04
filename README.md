## Purpose
-This repository was created in order to understand how a real-world web application is deployed using Docker

-Implemented a **multi-container architecture** instead of a single container setup

-Used Nginx as a **reverse proxy** to route requests to WordPress (PHP-FPM)

-Learnt how **separating services** (Nginx, WordPress, MySQL) makes the system more production-like

-Understood how Docker networks enable communication between different services

-Used .env for managing database credentials and configuration cleanly

-Implemented volumes for persistent storage so data is not lost on restart

-Faced and debugged real issues like database connection errors and misconfiguration

-Gained a clear understanding of request flow: **browser → Nginx → backend → database**
