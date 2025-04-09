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


📸 Screenshots

(https://github.com/user-attachments/assets/6d0d2811-90ea-4d0c-bbc9-d8975317cf5d)


🛠️ Known Issues
🔐 Login not working on Vercel due to production Clerk + AI API issues

✅ Fully working on localhost — recommended for testing

📬 Contact
📧 sameersaurabh658@gmail.com
🔗 GitHub Profile


