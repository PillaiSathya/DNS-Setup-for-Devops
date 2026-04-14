# 🌐 DNS Setup for DevOps Project

This project is part of my DevOps learning journey from roadmap.sh.  
It demonstrates how to configure a custom domain, DNS records, and deploy applications using both GitHub Pages and AWS EC2.

---

## 🚀 Project Objective

To learn and implement basic DNS setup by:

- Purchasing and configuring a custom domain
- Connecting domain to GitHub Pages
- Hosting a static website on AWS EC2
- Mapping subdomains using DNS records (A record & CNAME)

---

## 🏗️ Architecture Overview
sathyadevops.online
│
├── www → GitHub Pages (Static Portfolio)
│
└── app → AWS EC2 (Nginx Server)


---

## 🛠️ Technologies Used

- DNS Management (Namecheap)
- GitHub Pages
- AWS EC2 (Ubuntu)
- Nginx Web Server
- HTML, CSS
- SSH for server access

---

## 📌 What I Did

### 1️⃣ Domain Setup
- Purchased domain: `sathyadevops.online`
- Configured DNS using Namecheap

---

### 2️⃣ GitHub Pages Deployment
- Created a portfolio website
- Hosted using GitHub Pages
- Connected custom domain using CNAME record

👉 Live URL:
https://www.sathyadevops.online

---

### 3️⃣ AWS EC2 Deployment
- Launched Ubuntu EC2 instance
- Installed Nginx web server
- Uploaded portfolio files to server
- Configured domain mapping using A record

👉 Live URL:
http://app.sathyadevops.online

---

### 4️⃣ DNS Configuration
Configured the following records:

#### GitHub Pages
- CNAME:
  - `www → PillaiSathya.github.io`

#### EC2 Server
- A Record:
  - `app → EC2 Public IP (54.173.74.42)`

---

## ⚠️ Key Learning

- EC2 public IP can change unless Elastic IP is used
- DNS propagation takes time (5–30 mins)
- A record points domain to IP address
- CNAME maps subdomain to another domain

---

## 🧠 Challenges Faced

- DNS propagation delay
- EC2 IP change after restart
- GitHub Pages custom domain validation issue
- SSH key permission issues

---

## 🎯 Outcome

Successfully built a working multi-host deployment system using:

- Static hosting (GitHub Pages)
- Cloud server hosting (AWS EC2)
- Custom domain with DNS routing

---

## 🚀 Future Improvements

- Add HTTPS using SSL (Let’s Encrypt)
- Use Elastic IP for stable EC2 address
- Automate deployment using CI/CD pipeline
- Containerize application using Docker

---

## 👩‍💻 Author

Sathya  
DevOps Learning Journey 🚀