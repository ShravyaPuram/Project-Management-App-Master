# 🚀 Project Management Application with AWS

This is a full-stack Project Management Dashboard that allows users to manage projects, tasks, teams, and timelines effectively. Built with modern technologies like **Next.js**, **Tailwind CSS**, and **PostgreSQL**, and integrated with **AWS Lambda** and **Cognito** for scalability and security.

---

## 📚 Table of Contents

- [About](#about)
- [Tech Stack](#tech-stack)
- [Environment Variables](#environment-variables)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Run Locally](#run-locally)
  - [Deployment](#deployment)
- [Contact](#contact)

---

## 🌟 About

This Project Management App provides the ability to:
- Create and manage multiple projects.
- Assign tasks to users.
- Track progress using a responsive dashboard.
- Authenticate users securely using AWS Cognito.
- Run backend logic with AWS Lambda for scalability.

---

## 🧰 Tech Stack

### Frontend
- React.js
- Next.js
- Tailwind CSS
- TypeScript
- Material UI Data Grid

### Backend
- Node.js
- Express.js
- PostgreSQL
- Prisma ORM

### Cloud & Auth
- AWS Lambda
- AWS Cognito

---

## 🔐 Environment Variables

To run this project, add the following environment variables to your `.env` file:

```
DATABASE_URL=your_postgres_url
NEXTAUTH_SECRET=your_nextauth_secret
AWS_ACCESS_KEY_ID=your_aws_key
AWS_SECRET_ACCESS_KEY=your_aws_secret
COGNITO_CLIENT_ID=your_cognito_client_id
COGNITO_POOL_ID=your_cognito_pool_id
```

---

## 🛠️ Getting Started

### ✅ Prerequisites

- Node.js installed — [https://nodejs.org/](https://nodejs.org/)
- PostgreSQL installed or use a cloud database
- AWS account with Lambda and Cognito setup

---

### ⚙️ Installation

Clone the repo:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

Install dependencies:

```bash
npm install
```

---

### ▶️ Run Locally

```bash
npm run dev
```

Open `http://localhost:3000` in your browser to view the app.

---

## 🚀 Deployment

You can deploy this project on **Vercel** for the frontend and use **AWS Lambda** for serverless backend logic.

For Vercel deployment:
- Push code to GitHub
- Import repo to [https://vercel.com/](https://vercel.com/)
- Set environment variables in Vercel dashboard
- Deploy ✅

---

> 💡 *If you found this project useful, feel free to give it a ⭐️ on GitHub!*
