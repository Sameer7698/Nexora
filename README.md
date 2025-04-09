# 🧠 AI Career Coach

A full-stack AI-powered career guidance platform built using **Next.js**, **Neon DB**, **Clerk**, **Inngest**, **Shadcn UI**, and **Gemini AI**.

---

## 🚀 Live Demo

🌐 [https://aicareercoach-chi.vercel.app](https://aicareercoach-chi.vercel.app)

⚠️ **Note**: The live site’s login is currently **not working** due to deployment issues with **Clerk authentication** on Vercel and **AI integration**.  
✅ The app works perfectly in **local development**.

---

## 🎯 Features

- ✨ AI-powered career recommendations using Gemini API
- 🔐 Authentication via Clerk
- 📄 Resume analysis and smart feedback
- 📬 Email onboarding with background tasks using Inngest
- 🎨 Beautiful and responsive UI with Shadcn UI + Tailwind CSS
- 🧾 Data stored using Prisma + Neon DB (PostgreSQL)

---

## 📦 Tech Stack

- **Frontend**: Next.js, Tailwind CSS, Shadcn UI
- **Backend**: Prisma ORM, Inngest (background jobs)
- **Database**: Neon (serverless PostgreSQL)
- **Authentication**: Clerk.dev
- **AI**: Gemini API (Google)
- **Deployment**: Vercel

---

## 🖥️ Local Setup

> Clone and run the project locally with the steps below:

```bash
git clone https://github.com/your-username/ai-career-coach.git
cd ai-career-coach
npm install

🔐 Create .env.local and add your variables:
DATABASE_URL=your_neon_connection_string

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
CLERK_SECRET_KEY=your_clerk_secret

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=your_gemini_key

🗂 Migrate database and run:
npx prisma migrate dev
npm run dev

## 📸 Screenshots

### 🏠 Home Page
![Home Page](https://github.com/user-attachments/assets/757fb393-ebcc-4d3f-8ecd-d63cfcf57c13)

---

### 🏭 Industry Insight Section
![Industry Insight](https://github.com/user-attachments/assets/89b3403d-88ac-4b3e-a6ba-a910bac88c51)

---

### 🎯 Interview Prep Section
![Interview Prep](https://github.com/user-attachments/assets/e754b580-6d43-47ae-aa8f-f753cba87950)

---

### 📝 Cover Letter Section
![Cover Letter](https://github.com/user-attachments/assets/fb961175-6c35-40f0-9cde-005bcbb98cf6)

---

### 📄 Resume Builder
![Resume Builder](https://github.com/user-attachments/assets/3101facd-4e89-46d3-a06c-68e5baedd988)


🛠️ Known Issues
🔐 Login not working on Vercel due to production Clerk + AI API issues

✅ Fully working on localhost — recommended for testing


📬 Contact
📧 sameersaurabh658@gmail.com
🔗 GitHub Profile

 


 
