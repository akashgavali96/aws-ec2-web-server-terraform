# aws-ec2-web-server-terraform
Provisioned a web server using Terraform on AWS. Automated installation of Apache web server and deployed a custom HTML webpage using user data script.

🚀 AWS EC2 Web Server using Terraform

📌 Project Overview

This project demonstrates how to provision a web server on AWS using Terraform. The infrastructure is defined as code to automatically create an EC2 instance and configure it to host a web application.

---

🛠️ Technologies Used

* AWS EC2
* Terraform
* Amazon Linux (AMI)
* Apache (httpd) Web Server
* HTML

---

⚙️ What This Project Does

* Provisions an EC2 instance using Terraform
* Uses Amazon Linux AMI for the server
* Installs and configures Apache web server using user data script
* Deploys a custom HTML webpage automatically
* Makes the webpage accessible via public IP

---

📂 Project Structure

* `main.tf` → Terraform configuration file

---

🚀 How to Run This Project

1. Install Terraform and AWS CLI
2. Configure AWS credentials:

   ```
   aws configure
   ```
3. Initialize Terraform:

   ```
   terraform init
   ```
4. Preview infrastructure:

   ```
   terraform plan
   ```
5. Deploy resources:

   ```
   terraform apply
   ```
6. Copy EC2 Public IP and open in browser

---

🌐 Output

A running web server displaying:
**"Hello from Terraform 🚀"**

---

🎯 Key Learnings

* Infrastructure as Code (Terraform basics)
* AWS EC2 provisioning using Terraform
* Automating server setup using user data
* Difference between manual vs automated deployment

---

🚀 Future Improvements

* Add Security Groups using Terraform
* Use Key Pair for SSH access
* Deploy Load Balancer using Terraform
* Implement Auto Scaling

---
