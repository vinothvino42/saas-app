# SaaS App - LMS with Next.js, Supabase & Payments

A LMS SaaS app featuring user authentication, subscriptions, and payments using Next.js, Supabase, and Stripe! You'll build and deploy a real-time teaching platform with Vapi, integrate an AI vocal agent, and deliver seamless, interactive learning sessions.

## ⚙️ Tech Stack

- [Vapi](https://vapi.ai/)
- [Supabase](https://supabase.com/)
- [Clerk](https://clerk.com/)
- [Sentry](https://sentry.io/)
- [Shadcn/UI](https://ui.shadcn.com/)
- [Zod](https://zod.dev/)
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/saas-app.git
cd saas-app
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

You can obtain these credentials by signing up on: [Supabase](https://supabase.com/dashboard), [Clerk](https://jsm.dev/converso-clerk), [Sentry](https://jsm.dev/converso-sentry), [Vapi](https://jsm.dev/converso-vapi).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## 🎖️ Credits

This repository contains the code corresponding to an in-depth tutorial available on <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a> YouTube channel. Watch [SaaS App Tutorial](https://www.youtube.com/watch?v=XUkNR-JfHwo).
