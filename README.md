# How to Dockerize a React App and Deploy It Easily

## 📁 Project Structure

- **frontend**: This directory contains the code for the frontend part of the project, usually a React application. It also has a `Dockerfile` and a `docker-compose.yaml` file to build and run the frontend service using Docker.
- **backend**: This directory contains the code for the backend part of the project, usually a Node.js API server. It also has a `Dockerfile` and a `docker-compose.yaml` file to build and run the backend service using Docker.
- **README.md**: This file provides a brief overview of the project, its features, and how to run it locally. It also links to the corresponding blog post for more details and explanations.

## 🚀 How to Run a Project

To run a project locally, you need to have Docker and Node.js installed on your machine. Then, follow these steps:

1. Clone this repository or download the project folder you want to run.
2. Navigate to the project folder and open a terminal window.
3. Run `docker-compose up` to build and start the frontend and backend services¹[1].
4. Open your browser and go to `http://localhost:3000` to see the frontend app.
5. You can also use tools like Postman or curl to test the backend API endpoints at `http://localhost:8000/api`.

