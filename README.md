☁️ Bhavesh CloudVerse — Docker Web Application

A modern, responsive cloud-themed website built using HTML and CSS, containerized with Docker, and deployed on an AWS EC2 instance.

🚀 Project Overview

Bhavesh CloudVerse is a personal cloud-learning website that showcases my journey in cloud computing and containerization. The application is packaged inside a lightweight Nginx Docker image and can be deployed on an AWS EC2 virtual server.

✨ Features

- Modern dark-themed user interface
- Responsive web design
- Personal branding — Bhavesh CloudVerse
- Cloud computing technology showcase
- Docker-based application deployment
- Lightweight Nginx web server
- AWS EC2 hosting environment

🛠️ Technologies Used

- HTML5 — Website structure
- CSS3 — Styling and responsive layout
- Docker — Application containerization
- Dockerfile — Automated image creation
- Nginx Alpine — Lightweight web server
- AWS EC2 — Cloud server deployment
- Linux — Server administration

📂 Project Structure

Bhavesh-CloudVerse/
├── Dockerfile
├── index.html
└── README.md

🐳 Run the Application with Docker

1. Clone the repository

git clone https://github.com/patilbhavesh1008-arch/Bhavesh-CloudVerse.git
cd Bhavesh-CloudVerse

2. Build the Docker image

docker build -t bhavesh-cloudverse:v1 .

3. Run the Docker container

docker run -d --name bhavesh-cloudverse -p 8080:80 bhavesh-cloudverse:v1

4. Access the application

Open your browser and visit:

http://localhost:8080

For AWS EC2 deployment, use your instance's public IP with port "8080", after allowing inbound TCP traffic on that port in the EC2 security group.

📄 Dockerfile

FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 80

🎯 Learning Outcomes

- Understanding Docker images and containers
- Creating a custom Docker image using a Dockerfile
- Deploying a static website using Nginx
- Running containerized applications on AWS EC2
- Practicing Linux commands and cloud deployment

👨‍💻 Author

Bhavesh Patil

Cloud Computing | AWS | Docker | Linux

GitHub: "patilbhavesh1008-arch" (https://github.com/patilbhavesh1008-arch)

---

⭐ If you find this project useful, feel free to explore the repository.

Learn. Build. Deploy. — Bhavesh CloudVerse
