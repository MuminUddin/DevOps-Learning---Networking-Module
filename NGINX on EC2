# 📌 Project: Deploy NGINX on EC2 and Route Custom Domain via DNS

### Objective:
Set up a basic web server using AWS EC2, install NGINX, and point a custom domain to the instance using Route 53.

---

## ✅ Steps Completed:

### 1. Domain Registration
- Registered `muminlabs.com` via AWS Route 53
- Disabled auto-renewal (as this is for learning purposes)

### 2. EC2 Instance Setup
- Launched an EC2 instance using Amazon Linux 2023
- Created a new key pair for secure SSH access (`muminlabs-key.pem`)
- Configured security group to allow:
  - SSH (port 22) from my IP
  - HTTP (port 80) from anywhere

### 3. Connected via SSH
```bash
ssh -i "muminlabs-key.pem" ec2-user@<public-ip>
