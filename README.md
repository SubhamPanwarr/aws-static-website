# AWS Static Website Deployment

This project demonstrates how to deploy a simple static website on an AWS EC2 instance running Ubuntu and Nginx.

## Steps to Run

1. Launch an EC2 instance (Ubuntu, t2.micro, public IP)
2. SSH into the instance
3. Run:

```bash
sudo apt update
sudo apt install nginx -y
echo "<h1>Hello from EC2!</h1>" | sudo tee /var/www/html/index.html

## Project URL
https://roadmap.sh/projects/ec2-instance
