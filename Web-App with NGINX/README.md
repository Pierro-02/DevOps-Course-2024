# Web Application with NGINX 🌐

This project is a simple web application containerized with Docker and hosted using NGINX. It serves a static index.html file, providing a basic webpage. By utilizing Docker, the application becomes highly portable and straightforward to deploy in various environments.

## Project Overview

The structure of this project includes the following essential files:

- **Dockerfile**: Specifies the steps to create a Docker image, using NGINX to serve the application.
- **index.html**: The core HTML file containing the content displayed on the webpage.
- **index**: An additional configuration file or placeholder, adaptable to your specific use case.

## Highlights 🚀

- Serves a static webpage through an NGINX web server.
- Fully containerized for portability and ease of deployment.
- Simple, lightweight, and efficient design.

## How to Get Started 🛠️

Follow the instructions below to set up and run the project locally:

### Steps to Run the Application 🚀

1. Clone the repository to your system:

```bash
   git clone <[repository-url](https://github.com/zaibunnisaq/DevOps-Course-2024/Docker_NGINX-Web-App)>
   cd <[repository-directory](https://github.com/zaibunnisaq/DevOps-Course-2024)>
```
2. Build the Docker image for the application:

```bash
   docker build -t <your-docker-username>/my-webpage:latest .
```

3. Launch the application in a Docker container:

```bash
   docker run -d -p 8080:80 <your-docker-username>/my-webpage:latest
```

4. Open your browser and access the application:

```bash
   http://localhost:8080
```
## Publishing to Docker Hub 📦
To share your Docker image on Docker Hub, follow these steps:

- Tag the Docker image:
```bash
docker tag <your-docker-username>/my-webpage:latest <your-docker-username>/my-webpage:v1
```
- Push the image to Docker Hub:
```bash
docker push <your-docker-username>/my-webpage:v1
```

