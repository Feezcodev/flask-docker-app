# Containerized Flask Application

A lightweight Flask web application containerized using Docker and deployed on a WSL2 Ubuntu environment.

## 🚀 Features
* Flask web server running inside a Python slim Docker container.
* Isolated environment using WSL2 and Docker Desktop.
* Mapped port configuration for local browser accessibility.

## 🛠️ Prerequisites
Make sure you have the following installed on your system:
* Windows Subsystem for Linux (WSL2 with Ubuntu)
* Docker Desktop

## 📦 Project Structure
```text
flask-docker-app/
├── app.py
├── Dockerfile
└── requirements.txt

## Screenshots

| App Code & Dockerfile | Build Success | Running Server | Browser Output | Repository Files |
| :---: | :---: | :---: | :---: | :---: |
| ![App Code](screenshots/01-flask-app-code-and-dockerfile.PNG) | ![Build Success](screenshots/02-docker-build-success.PNG) | ![Server Running](screenshots/03-flask-server-running-in-terminal.PNG) | ![Browser Output](screenshots/Browser%20Verification.PNG) | ![Repo Files](screenshots/05-github-repository-files.PNG) |