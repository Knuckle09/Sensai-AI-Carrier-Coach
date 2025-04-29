Here is a curated and professional `README.md` for your **AI Career Coach** project, following the style of the plant disease detection app example you gave:

---

# 🎯 AI Career Coach – Personalized Career Guidance Web App

This repository contains a fully functional AI-powered career coaching web application designed to assist users in identifying their career interests and recommending relevant career paths and skill development plans.

The application is deployed on **Vercel** and uses **Clerk authentication** for secure login and **Supabase** as a backend database. It provides a seamless and intelligent experience for users seeking clarity in their career journey.

---

## 📘 Brief Description

**AI Career Coach** helps users navigate their career choices through AI-driven recommendations based on their inputs and preferences.

✅ **Personalized Career Suggestions** – Tailored role recommendations powered by OpenAI based on user interests and goals  
✅ **Real-Time Chat Interface** – Engage with a career coach chatbot to ask queries or seek suggestions  
✅ **Onboarding Flow** – Smooth and dynamic onboarding to capture user background and interests  
✅ **User Authentication** – Secure signup/login using Clerk  
✅ **Dashboard Interface** – Clean, responsive user dashboard to track and manage preferences  
✅ **Database Integration** – Supabase used to manage user data and preferences

This solution is ideal for students, fresh graduates, or professionals exploring a shift in their career path. It brings together AI and intuitive UI/UX to offer clarity in career planning.

---

## 🧰 Tech Stack

- **Frontend:** ReactJS, Next.js 14 App Router, Tailwind CSS, ShadCN UI  
- **Backend:** Node.js, Supabase (PostgreSQL), Prisma ORM  
- **Authentication:** Clerk.dev  
- **AI Integration:** OpenAI GPT  
- **Hosting:** Vercel  
- **Database Client:** Prisma  
- **Additional Libraries:** Axios, lucide-react, zustand, shadcn/ui

---

## 📌 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-career-coach.git
cd ai-career-coach
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Environment Setup

Create a `.env` file in the root directory and add the following variables:

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
DATABASE_URL=your_supabase_database_url

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=your_google_gemini_api_key (if used)
```

---

### 4️⃣ Run the App Locally

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to use the app.

---

## 🚀 Deployment on Vercel

To deploy:

1. Push your code to GitHub  
2. Connect the repo on [vercel.com](https://vercel.com)  
3. Add your environment variables in Vercel's dashboard  
4. Click **Deploy**

---

## 📂 Project Structure

```
/app
   /dashboard           → Main user dashboard
   /onboarding          → Onboarding steps
   /auth                → Clerk auth pages
/lib                    → Prisma client and helpers
/actions                → Server actions for database and auth
/components             → All reusable UI components
/styles                 → Tailwind + global styles
/prisma/schema.prisma   → Database schema definition
```

---

## 📸 Screenshots

Feel free to view detailed screenshots in the `/assets` or GitHub issue tracker.

---

## 📝 Additional Notes

- Ensure Supabase tables (`User`, `Onboarding`, etc.) are created before running.
- You can customize the career coach prompts in `/lib/utils.js`.
- For local testing, test Clerk auth using the developer dashboard and test users.

---

## 👨‍💻 Built By

Developed with ❤️ by [Sai Samarth Sangamesh Budihal] – CSE Student passionate about AI and career development tools.

## Demo Images

![image](https://github.com/user-attachments/assets/2bdda97b-953f-4e06-b67f-56eab15454a3)
![image](https://github.com/user-attachments/assets/e3418e53-7b95-4475-b1c0-d7427b56fa21)
![image](https://github.com/user-attachments/assets/2b3e4d5f-3e7c-43d2-99f2-fcf3e0e41f1e)
![image](https://github.com/user-attachments/assets/74b34481-48c1-41a3-935e-4ce5a6143658)
![image](https://github.com/user-attachments/assets/adbb2e4f-39c3-4d51-8c09-43985672f7e0)
![image](https://github.com/user-attachments/assets/c0c076c9-70af-4ca9-865e-87613150a184)
![image](https://github.com/user-attachments/assets/3b1f65e7-5413-41c2-8d23-6753198e8951)
![image](https://github.com/user-attachments/assets/be57c0ba-3190-42a5-b28b-1022fa458e7d)
![image](https://github.com/user-attachments/assets/3e2165a8-c7be-4cad-836a-9ac44a796cd6)
![image](https://github.com/user-attachments/assets/d6fad4cc-3e1d-4bc7-a6be-20a7d3c050f9)
![image](https://github.com/user-attachments/assets/cf19e989-37fd-4058-90a2-04b5d1fd4cb7)
![image](https://github.com/user-attachments/assets/027f919d-4681-4134-b24d-1136f88f73fc)
![image](https://github.com/user-attachments/assets/aca2821c-03fa-4e83-9b01-f1f94efd61b5)
![image](https://github.com/user-attachments/assets/0cc5fea1-8eb2-4dfd-bd2e-da483200d4ae)
![image](https://github.com/user-attachments/assets/17194dcf-556e-49c8-a2c4-d12767d80be2)
![image](https://github.com/user-attachments/assets/f68fee68-70f3-4dd2-98a0-e239333a4dd6)
![image](https://github.com/user-attachments/assets/109c6b28-323f-44bb-bdc7-221ab60be88f)
![image](https://github.com/user-attachments/assets/40288c46-e3c5-446f-8364-dc82fdf9dccb)

