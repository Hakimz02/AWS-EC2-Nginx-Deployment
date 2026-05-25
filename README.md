AWS EC2 Nginx Web Server Deployment

📌 Project Overview
This project demonstrates how to deploy a basic web server on an AWS EC2 instance using Ubuntu and Nginx. The server is made publicly accessible through AWS Security Group configuration.

🎯 Objective
- Launch a virtual server on AWS EC2
- Connect to the server using SSH
- Install and run Nginx web server
- Configure network access using AWS Security Groups
- Host a web page accessible via public IP

🧱 Architecture

Browser → Internet → AWS EC2 Instance → Nginx Web Server → Web Page Response

⚙️ Technologies Used
- Amazon EC2
- Ubuntu Linux
- Nginx
- SSH
- AWS Security Groups

🚀 Steps Performed

 1. Launch EC2 Instance
- Created an Ubuntu EC2 instance on AWS
- Generated and downloaded SSH key pair (.pem file)

2. Connect via SSH
```bash
ssh -i project1.pem ubuntu@<your-public-ip>
