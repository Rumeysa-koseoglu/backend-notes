# What Is Backend And How Does It Works

Every website we browse consists of two main parts:

1. Frontend -> The part that users see (visual interface: buttons, texts, images etc.)

2. **Backend** -> Invisible and background running system (server, database, processes)

The backend takes care of data. It follows called businnes logic, talks to the database, and sends answers back to the user. It works in the background, so users dont't see it directly.

## What Is The Use of Backend?

- Receives user's request
- Performs operations on the server
- Communicates with the database
- Sends responses back to the frontend

## How Does the Backend Work

The backend of a website is usually consists of 3 main components:

### 1. Server

A computer that listens to and processes requests from users. This computer is open 24/7 and runs the web application. It is usually written in backend languages such as Node.js, Python, PHP

### 2. Application

This is the part where we write the logic. Example;

- How to register as a new user
- How to add a product to the cart
- How to verify password
  (We write these logics with backend languages)

### 3. Database

The data needed by the application is stored here. Eg; User information, products, order history..

- Popular databases: MySQL, PostgreSQL, MongoDB

## Backend Languages and Frameworks

- **Node.js** - Express.js, NestJS
- **Python** Django, Flask
- **PHP** Laravel
- **Ruby** Ruby on Rails
- **Java** Spring Boot

## How Backend and Frontend Communicate

Frontend sends HTTP requests like:

- `GET /products`
- `POST /login`

Backend receives the request, performs operations, and sends a JSON response.
