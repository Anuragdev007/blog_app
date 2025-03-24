# Blog App with Spring Boot

A simple and robust blog application built using Spring Boot. This application provides a foundation for creating, reading, updating, and deleting blog posts, along with user authentication and other essential features.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Overview
The Blog App is a full-stack web application that demonstrates how to build a scalable and maintainable blog using Spring Boot. The app includes features such as:
- User authentication and authorization
- CRUD operations for blog posts
- RESTful API endpoints for integration
- Responsive design with a modern front-end

## Features
- **User Management:** Register, login, and manage user profiles.
- **Blog Management:** Create, update, delete, and view blog posts.
- **Comment System:** Add and manage comments on posts.
- **Search & Pagination:** Easily navigate through posts with search and pagination support.
- **Security:** Secure endpoints using Spring Security.

## Technologies
- **Backend:** Spring Boot, Spring MVC, Spring Data JPA, Spring Security
- **Database:** PostgreSQL
- **Build Tool:** Maven
- **Frontend:** Thymeleaf templates 
- **Others:** Lombok, MapStruct, etc.

## Prerequisites
- Java 11 or higher
- Maven 3.6 or higher
- Git

## Installation

 **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/blog_app.git
   cd blog_app

   # Server configuration
server.port=8080


# JPA configuration
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
