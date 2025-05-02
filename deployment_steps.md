# 🧾 EC2 Flask App Deployment Guide

### 1. Launch EC2 Instance
- Ubuntu 24.04, t3.micro
- Add inbound rules for ports 22 (SSH), 5000 (Flask)

### 2. Connect via SSH
```bash
ssh -i my-key.pem ubuntu@56.228.23.184
