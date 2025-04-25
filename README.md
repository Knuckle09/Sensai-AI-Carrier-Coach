# Sensai-AI-Carrier-Coach

Here's a **detailed GitHub repository description** for your AI Career Coach project, including a well-structured **overview**, **features**, **tech stack**, **setup instructions**, and **contribution guidelines**—everything a polished GitHub repo needs:

---

# 🧠 AI Career Coach

**AI Career Coach** is a smart, full-stack career guidance web application built to help users receive personalized, AI-powered feedback on their resumes, cover letters, and career paths. It offers intelligent industry insights, tailored improvement tips, and a user-friendly interface to guide individuals in advancing their professional journey.

---

## 🚀 Features

- 🔐 **Clerk Authentication** for secure sign-up/sign-in and user session management  
- 👤 **User Onboarding** flow for profile creation and industry selection  
- 📑 **Resume and Cover Letter Analysis** with AI-generated feedback and ATS scoring  
- 🧠 **Skill-Based Assessments** with categorized quizzes, score tracking, and improvement tips  
- 📊 **Industry Insight Dashboard** that visualizes trends, salary data, and suggested skills  
- 🌐 **Role-Based Career Suggestions** using real-time data linked to industry trends  
- 💾 **Persistent User Data** via PostgreSQL and Prisma ORM  
- 🌈 **Responsive UI** with intuitive design built using TailwindCSS and Next.js (App Router)  
- ☁️ **Deployed on Vercel** for reliable and fast production performance  

---

## 🛠 Tech Stack

| Category              | Tools/Technologies |
|-----------------------|--------------------|
| **Frontend**          | Next.js (App Router), React.js, TailwindCSS |
| **Authentication**    | Clerk |
| **Database**          | Supabase (PostgreSQL), Prisma ORM |
| **Backend**           | Server Actions with Next.js, Prisma Queries |
| **Deployment**        | Vercel |
| **API/Communication** | Axios |
| **Dev Tools**         | .env configuration, Git, GitHub, Vercel CLI |

---

## 📁 Folder Structure

```
ai-career-coach/
├── app/                # Next.js App Router pages and components
├── lib/                # Prisma client, helper functions
├── prisma/             # Prisma schema and migrations
├── public/             # Static assets
├── styles/             # TailwindCSS configuration
├── .env                # Environment variables
├── package.json        # Project metadata and dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Getting Started (Local Development)

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/ai-career-coach.git
cd ai-career-coach

# 2. Install dependencies
npm install

# 3. Configure environment variables
cp .env.example .env
# Add your Supabase, Clerk, and Prisma credentials in .env

# 4. Push the Prisma schema and generate client
npx prisma generate
npx prisma migrate dev

# 5. Run the development server
npm run dev
```

---


