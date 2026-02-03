🚀 Strapi Task-1 — Blog Content Modeling (DevOps Internship)

Author: Deepak Vishwakarma
Role: Aspiring Cloud & DevOps Engineer
Task: Internship Pre-Evaluation (Task-1)

✨ Overview

This repository contains my Task-1 submission for the DevOps Internship program.

The goal of this task was to set up Strapi v5 locally, understand its architecture, work with the admin panel, design a Blog content model, manage content, and submit the work using a proper GitHub Pull Request workflow.

Rather than just completing steps, I focused on understanding how a real CMS fits into modern Cloud & DevOps environments.

🧰 Tech Stack

Strapi v5 (Headless CMS)

Node.js

JavaScript

SQLite (default local database)

Git & GitHub

⚙️ Local Setup Guide
1️⃣ Clone the Repository
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
Field	Type
title	Text
description	Rich Text
author	Text

This schema mirrors a real-world content model commonly used in production systems.

📝 Content Management

Created multiple blog entries

Added structured and meaningful content

Used Draft → Publish workflow

Verified schema changes reflect correctly in the Content Manager

This helped me understand schema → data → API flow in headless CMS platforms.

🔁 GitHub Workflow

To follow professional practices, I used a GitHub Pull Request–based workflow:

Initialized Git repository correctly

Used feature branches

Committed meaningful changes

Raised a Pull Request for review

🔗 Pull Request:
👉 https://github.com/Imdpkk/strapi-task-1/pull/1

🎥 Loom Walkthrough

A Loom video is recorded demonstrating:

Strapi running locally

Admin dashboard

Blog content type

Published blog entries

GitHub repository & PR

📹 Loom Link: (submitted via Excel & Teams)

🧠 Key Learnings

This task helped me gain practical understanding of:

Headless CMS concepts

Strapi v5 UI and architecture

Content modeling and schema evolution

Admin panels used in real products

Debugging setup issues independently

Clean Git & PR workflows under real constraints

Most importantly, it taught me how backend systems are actually used before deployment.

☁️ Relevance to Cloud & DevOps

This task strongly aligns with my Cloud & DevOps learning journey:

Strapi apps can be containerized with Docker

Easily deployable on AWS / GCP / Azure

Works well with CI/CD pipelines

Represents a real backend service used in production

Reinforces the idea that DevOps starts with understanding applications

You can’t automate or scale what you don’t understand — this task helped bridge that gap.

🔮 Future Enhancements

If extended further, I would:

Dockerize the Strapi application

Deploy it on a cloud VM or Kubernetes cluster

Add CI/CD using GitHub Actions

Secure secrets via environment variables

Integrate a frontend (React / Next.js)

Apply role-based access and API security

🎯 Final Note

This task was not just about completing instructions —
it was about learning how real backend systems are built, managed, and prepared for cloud deployment.

I’m highly motivated to continue learning, contributing, and growing as a Cloud & DevOps Engineer through this internship.

Thank you for the opportunity.
