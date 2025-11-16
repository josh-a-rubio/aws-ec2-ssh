# 🚀 EC2 SSH Lab

## 🧾 Overview
This demo demonstrates launching multiple AWS EC2 instances in different regions and connecting to them via SSH using key-based authentication. The purpose is to show practical skills, including multi-region instance management and secure access.

## 🏗️ Architecture
- **Regions:** us-east-1 (N. Virginia), ap-northeast-1 (Tokyo)  
- **OS:** Ubuntu Linux  
- **Authentication:** SSH private/public key pairs  
- **Security:** Restricted access via security groups

## 🛠️ Requirements
- AWS account with permissions to launch EC2 instances  
- SSH client (e.g., macOS Terminal, Linux Terminal, or PuTTY on Windows)  
- Generated SSH key pair for connecting to instances  
- Basic understanding of Linux commands

## 📚 Documentation
- Screenshots of EC2 instance configuration and SSH sessions are stored in the [`screenshots/`](./02-screenshots/) folder  
- Presentation slides are in the [`slides/`](./03-slides/) folder  
- Demo video is in the [`demo/`](./04-demo/) folder  

## 🔒 Security Notes
- Never share your private SSH key (`.pem`)  
- Security groups should restrict SSH access to your IP only  
- Password authentication should be disabled after setting up SSH key authentication  
- Only authorized public keys should be added to `~/.ssh/authorized_keys` on the server

## 📁 Repo Structure
```
ec2-ssh-lab/
├── README.md
├── LICENSE
├── screenshots/
├── slides/
└── demo/
```

## 📄 License
This project is released under the MIT License. See [LICENSE](LICENSE) for details.



