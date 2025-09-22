# 🚀 Mattermost Server on Docker (Self-hosted Slack Alternative)

## 📖 Overview
في المشروع ده قمت بنشر **Mattermost server** باستخدام **Docker** على **Windows Server 2019** كبديل لـ Slack.  
الهدف من الخطوة دي كان:
- نوفر منصة تواصل داخلية **self-hosted**.
- نضمن خصوصية البيانات (بدل ما تكون عند طرف خارجي).
- نوفر التكلفة الشهرية اللي بتاخدها SaaS solutions زي Slack.

---

## 🛠️ Tech Stack
- **OS**: Windows Server 2019  
- **Containerization**: Docker + Docker Compose  
- **App**: Mattermost Team Edition  

---

## ⚙️ Setup Steps

### 1. Install Docker on Windows Server
- نزل Docker Desktop أو Docker Engine.
- فعل WSL2 لو السيرفر بيدعم.

### 2. Clone the Repository
```bash
git clone https://github.com/USERNAME/docker-mattermost-setup.git
cd docker-mattermost-setup
