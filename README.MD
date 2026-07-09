# AWS DevOps Engineer Internship Assignment

## Objective
Deploy a simple website on an AWS EC2 instance using Nginx.

## AWS Services Used
- Amazon EC2
- Security Group

## Steps Performed

1. Launched an Ubuntu EC2 instance.
2. Created a Security Group.
3. Allowed ports 22 (SSH) and 80 (HTTP).
4. Connected using EC2 Instance Connect.
5. Updated packages.
6. Installed Nginx.
7. Verified Nginx service.
8. Created a custom HTML page.
9. Hosted the website using Nginx.

## Commands Used

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
df -h
free -h
ps aux
```

## Website

Accessible using the EC2 Public IP.

## Author

Jayesh Zimbal