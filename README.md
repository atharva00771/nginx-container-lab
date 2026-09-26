# 🐳 Docker Nginx Basics

A beginner-friendly Docker project demonstrating how to **pull the Nginx image from Docker Hub and run it as a container**.

## 📌 Project Overview

In this project, I practiced basic Docker commands by:

* Pulling the official Nginx Docker image
* Creating and running an Nginx container
* Mapping the container port to the local machine
* Accessing Nginx through a web browser
* Checking the running container using Docker commands

## 🛠️ Technologies Used

* Docker
* Nginx
* Ubuntu / WSL
* Docker Hub

## 🚀 Steps Performed

### 1. Pull Nginx Image

```bash
docker pull nginx
```

This downloads the official Nginx image from Docker Hub.

### 2. Run Nginx Container

```bash
docker run -d -p 8080:80 --name my-nginx nginx
```

### 🔍 Command Explanation

* `docker run` → Creates and starts a container
* `-d` → Runs the container in background
* `-p 8080:80` → Maps local port `8080` to container port `80`
* `--name my-nginx` → Gives the container a name
* `nginx` → Uses the Nginx Docker image

### 3. Check Running Container

```bash
docker ps
```

### 4. Open Nginx in Browser

Open:

```text
http://localhost:8080
```

If everything is working correctly, the **Welcome to nginx!** page will appear.

## 📸 Project Proof

### Nginx Container Running

Add your Docker terminal screenshot here.

### Nginx Welcome Page

Add your browser screenshot showing:

`http://localhost:8080`

## 🧹 Stop and Remove Container

Stop the container:

```bash
docker stop my-nginx
```

Remove the container:

```bash
docker rm my-nginx
```

## 📚 What I Learned

* Docker images and containers
* Pulling images from Docker Hub
* Running containers
* Port mapping
* Basic Docker container management
* Running Nginx inside a Docker container

## 👨‍💻 Author

**Atharva Avhad**

B.Tech AI & Data Science Student | Aspiring Data Analyst | AWS Cloud Enthusiast

