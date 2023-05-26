# Nginx WebSocket Proxy in Docker

This project provides a Dockerized Nginx server configured as a WebSocket proxy. It forwards all WebSocket connections received on a specified port to an upstream backend server.

## Purpose

The aim of this project is to create a secure WebSocket proxy using Nginx and Docker. This is particularly useful when you want to expose a WebSocket service running on a backend server to the internet, but you don't want to expose the backend server directly.

## Installation

To install and run this project, you need to have Docker installed on your machine. If you don't have Docker installed, you can download it from the [Docker website](https://www.docker.com/products/docker-desktop).

You also need to clone this repository to your local machine:

```bash
git clone https://gitlab.com/yourusername/nginx-websocket-proxy.git
cd nginx-websocket-proxy
```

Replace `yourusername` and `nginx-websocket-proxy` with your actual GitLab username and repository name.

## Running the Project

First, build the Docker image:

```bash
docker build -t nginx-websocket-proxy .
```

Next, run the Docker container:

```bash
docker run -p 8080:8080 -e BACKEND_HOST=your-backend-host nginx-websocket-proxy
```

Replace `your-backend-host` with your actual backend host.

The Nginx server is now running and listening for WebSocket connections on port 8080. All WebSocket connections received will be forwarded to the upstream backend server specified by the `BACKEND_HOST` environment variable.
