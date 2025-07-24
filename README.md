# Converso: Real-time AI Teaching Platform

> **Converso** is a modern, full-stack SaaS platform for real-time, voice-driven AI tutoring. Built with Next.js App Router, Clerk authentication, Supabase, and a beautiful, responsive UI powered by Tailwind CSS.

## ✨ Features

- **Modern UI**: Clean, responsive, and accessible design using Tailwind CSS and custom components.
- **AI Companions**: Create, customize, and launch AI-powered teaching companions for any subject or topic.
- **Voice Sessions**: Real-time, voice-based learning powered by OpenAI and 11Labs.
- **User Authentication**: Secure sign-in/sign-up with Clerk.
- **Session History**: Track your recent lessons and revisit previous sessions.
- **Bookmarks**: Save your favorite companions for quick access.
- **Personal Dashboard**: View your created companions, session stats, and more.
- **Supabase Integration**: Fast, scalable database and storage.

## 🚀 Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

2. **Set up environment variables:**

   - Copy `.env.example` to `.env.local` and fill in your Supabase and Clerk keys.

3. **Run the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open [http://localhost:3000](http://localhost:3000) in your browser.**

## 🖥️ UI Preview

![Converso UI Preview](public/readme/hero.png)

## 🛠️ Tech Stack

- [Next.js App Router](https://nextjs.org/docs/app)
- [Clerk](https://clerk.com/) (Authentication)
- [Supabase](https://supabase.com/) (Database)
- [OpenAI](https://openai.com/) (AI)
- [11Labs](https://elevenlabs.io/) (Voice)
- [Tailwind CSS](https://tailwindcss.com/)

## 📦 Project Structure

- `app/` — App Router pages, layouts, and routes
- `components/` — UI and feature components
- `lib/` — Utilities and server actions
- `constants/` — Static data and config
- `public/` — Static assets (icons, images)
- `types/` — TypeScript types

## 📄 License

MIT
