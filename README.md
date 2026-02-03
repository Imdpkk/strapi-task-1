# 🚀 Strapi Task-1 — Blog Content Modeling  
### DevOps Internship Pre-Evaluation

**Author:** Deepak Vishwakarma  
**Role:** Aspiring Cloud & DevOps Engineer  
**Task:** Internship Task-1  

---

## ✨ Overview

This repository contains my **Task-1 submission** for the DevOps Internship program.

The objective of this task was to set up **Strapi v5 locally**, explore its architecture, work with the **Admin Panel**, design a **Blog content model**, manage content using real CMS workflows, and submit the work through a **proper GitHub Pull Request process**.

Rather than only completing steps, I focused on understanding **how a production-grade CMS fits into modern Cloud and DevOps ecosystems**.

---

## 🧰 Tech Stack

- **Strapi v5** — Headless CMS  
- **Node.js**  
- **JavaScript**  
- **SQLite** (default local database)  
- **Git & GitHub**

---

## ⚙️ Local Setup Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Imdpkk/strapi-task-1.git
cd devops-internship/my-strapi-app
2️⃣ Install Dependencies
npm install
3️⃣ Run Strapi
npm run develop
4️⃣ Open Admin Panel
http://localhost:1337/admin
Create an admin account on first launch.

🧱 Content Architecture
I designed a Blog collection type using Strapi’s Content-Type Builder.

Blog Schema
Field Name	Type
title	Text
description	Rich Text
author	Text
This schema reflects a real-world content model commonly used in production-ready applications.

📝 Content Management
Created multiple blog entries

Added structured and meaningful content

Used Draft → Publish workflow

Verified schema changes in the Content Manager

This helped me understand the schema → data → API flow in headless CMS platforms.

🔁 GitHub Workflow
To follow professional development practices, I used a Pull Request-based Git workflow:

Initialized the repository correctly

Worked with feature branches

Committed meaningful changes

Raised a Pull Request for review

🔗 Pull Request Link:
👉 https://github.com/Imdpkk/strapi-task-1/pull/1

🎥 Loom Walkthrough
A Loom video is recorded demonstrating:

Strapi running locally

Admin dashboard overview

Blog content type

Published blog entries

GitHub repository & Pull Request

📹 Loom Link: (submitted via Excel & Teams)

🧠 Key Learnings
Through this task, I gained practical understanding of:

Headless CMS concepts

Strapi v5 UI and architecture

Content modeling and schema evolution

Real-world admin panels

Debugging setup issues independently

Clean Git and PR workflows under real constraints

Most importantly, I learned how backend systems are actually used before cloud deployment.

☁️ Relevance to Cloud & DevOps
This task strongly aligns with my Cloud & DevOps learning journey:

Strapi applications can be containerized using Docker

Easily deployable on AWS / GCP / Azure

Integrates well with CI/CD pipelines

Represents a real backend service used in production

Reinforces the principle that DevOps starts with understanding applications

You can’t automate or scale what you don’t understand —
this task helped bridge that gap.

🔮 Future Enhancements
If extended further, I would:

Dockerize the Strapi application

Deploy it on a Cloud VM or Kubernetes cluster

Implement CI/CD using GitHub Actions

Secure secrets via environment variables

Integrate a frontend (React / Next.js)

Apply role-based access control and API security

🎯 Final Note
This task was not just about completing instructions —
it was about learning how real backend systems are built, managed, and prepared for cloud deployment.

I am highly motivated to continue learning, contributing, and growing as a Cloud & DevOps Engineer through this internship.

Thank you for the opportunity.
