<div align="center">
  <br />
    <a href="https://ai-resume-builder-ajfm88.vercel.app" target="_blank">
      <img src="https://github.com/user-attachments/assets/f3eaef96-9674-4201-afeb-4deb3500ab6d">
    </a>
  <br />

  <br />
    <img src="https://img.shields.io/badge/-Next.js_15-black?style=for-the-badge&logo=next.js&logoColor=white"/>
    <img src="https://img.shields.io/badge/-React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
    <img src="https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
    <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
    <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white"/>
    <img src="https://img.shields.io/badge/-OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>

  <h3 align="center">📝 AI Resume Builder - Full-Stack SaaS Application 📄</h3>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔗 [Links](#links)
6. 🚀 [Tutorial](#tutorial)

## 🤖 <a name="introduction">Introduction</a>

A professional full-stack SaaS application that leverages the power of AI to help users create stunning resumes. Built with Next.js 15, this application features Stripe payment integration, ChatGPT-powered auto-fill, and a beautiful drag-and-drop interface for crafting the perfect resume.

To see a live demo of this project, please [click here](https://ai-resume-builder-ajfm88.vercel.app) or on the image/banner up top. After clicking on "Get Started" please feel free to create/use your own account, or to use the following credentials:

**Guest/Test Accounts Credentials:**
| Email | Password |
|-------|----------|
| test@user.com | t3st1ngus3r |
| guest@user.com | gu3stus3r! |

## <a name="tech-stack">⚙️ Tech Stack</a>

- ⚡ [Next.js 15](https://nextjs.org) - React framework for production.
- ⚛️ [React 19](https://react.dev) - UI library with latest features.
- 📘 [TypeScript](https://www.typescriptlang.org) - Type-safe JavaScript.
- 🎨 [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework.
- 🧩 [Shadcn UI](https://ui.shadcn.com) - Beautiful, accessible components.
- 🗄️ [PostgreSQL](https://www.postgresql.org) - Powerful relational database.
- 🔐 [Clerk](https://clerk.com) - Authentication with Multi-Factor Auth.
- 💳 [Stripe](https://stripe.com) - Payment processing & subscriptions.
- 🤖 [OpenAI API](https://openai.com) - ChatGPT-powered AI features.
- 📁 [Vercel Blob](https://vercel.com/storage/blob) - File storage solution.
- 📝 [React Hook Form](https://react-hook-form.com) - Performant form handling.
- 🖱️ [dnd-kit](https://dndkit.com) - Drag and drop toolkit.
- 🖨️ [react-to-print](https://github.com/gregnb/react-to-print) - Print/PDF export.

## <a name="features">🔋 Features</a>

👉 **Multi-step Form** - Intuitive resume building with React Hook Form.

👉 **Dynamic Form Arrays** - Add/remove sections with useFieldArray.

👉 **Drag-and-Drop** - Reorder resume sections with dnd-kit.

👉 **AI Auto-Fill** - ChatGPT-powered content suggestions.

👉 **Subscription Tiers** - Multiple pricing plans via Stripe Checkout.

👉 **Mobile Responsive** - Beautiful on all devices with Tailwind CSS.

👉 **Print/Save as PDF** - Export resumes using react-to-print.

👉 **URL State Management** - Shareable resume states.

👉 **Auto-Save** - Never lose your progress with custom auto-save hook.

👉 **File Uploads** - Profile photos via Vercel Blob storage.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- 🌳 [Git](https://git-scm.com)
- 🟢 [Node.js](https://nodejs.org/en)
- 📦 [npm](https://www.npmjs.com)

**Cloning the Repository**

```bash
git clone https://github.com/ajfm88/ai-resume-builder.git
cd ai-resume-builder
```

**Installation**

Install the project dependencies using npm:

```bash
npm install --legacy-peer-deps
```

**Set Up Environment Variables**

Create a `.env.local` file in the root directory and add your environment variables:

```env
# Database (Neon PostgreSQL)
POSTGRES_URL=
POSTGRES_PRISMA_URL=
POSTGRES_URL_NO_SSL=
POSTGRES_URL_NON_POOLING=
POSTGRES_USER=
POSTGRES_HOST=
POSTGRES_PASSWORD=
POSTGRES_DATABASE=

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL="/sign-in"
NEXT_PUBLIC_CLERK_SIGN_UP_URL="/sign-up"

# Vercel Blob Storage
BLOB_READ_WRITE_TOKEN=

# OpenAI
OPENAI_API_KEY=

# Stripe
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
NEXT_PUBLIC_STRIPE_PRICE_ID_PRO_MONTHLY=
NEXT_PUBLIC_STRIPE_PRICE_ID_PRO_PLUS_MONTHLY=
STRIPE_WEBHOOK_SECRET=

# App
NEXT_PUBLIC_BASE_URL="http://localhost:3000"
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="links">🔗 Links</a>

- [Next.js Documentation](https://nextjs.org/docs)
- [Shadcn UI Components](https://ui.shadcn.com)
- [Stripe Documentation](https://stripe.com/docs)
- [OpenAI API Reference](https://platform.openai.com/docs)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)
- [React Hook Form](https://react-hook-form.com/get-started)
- [dnd-kit Documentation](https://docs.dndkit.com)

## 🚀 <a name="tutorial">Tutorial</a>

This project is a heavily modified version of the following tutorial:
<br />

<a href="https://www.youtube.com/watch?v=ySqesLjz6K0"><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/151519281/289277158-1736fca5-a031-4854-8c09-bc110e3bc16d.svg"/></a>
