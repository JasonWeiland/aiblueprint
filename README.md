AI Blueprint – README.md

Welcome to AI Blueprint, the personalized AI learning platform for founders, creators, and beginner developers.

🚀 What is AI Blueprint?

AI Blueprint helps you generate a personalized AI learning roadmap based on your background, goals, and time commitment. Whether you're building an AI startup, learning to code with AI, or exploring tools for your profession, AI Blueprint gives you the structure and resources to grow with confidence.

🌐 Live Site

👉 getaiblueprint.com

🧰 Tech Stack

Frontend: Lovable (low-code)

Backend: Supabase (PostgreSQL, Auth, Edge Functions)

Deployment: Vercel

Auth: Supabase Auth (email/password)

AI Engine: OpenAI API (for blueprint generation)

Payments: Stripe Checkout (Pro plan)

🔑 Core Features

Guided onboarding survey to understand user goals

Personalized AI learning blueprints (OpenAI-powered)

Save and manage multiple blueprints

Bookmark learning resources in your personal library

Free and Pro plans with Stripe integration

🧭 User Journey

Sign up with email/password

Answer a short onboarding survey

Receive a tailored AI learning plan

Track progress, bookmark resources, explore new blueprints

Upgrade to Pro for unlimited plans and exclusive features

📁 Project Structure (Lovable/Supabase-Based)

/pages – Frontend UI flows (onboarding, dashboard, blueprint, profile)

/supabase/functions – Serverless Edge Functions for AI calls

/db – Supabase schema and policies

/public – Brand assets and static files

📦 Setup (For Developers)

Note: This project is built in Lovable. Code lives in GitHub, backend in Supabase, deployment via Vercel.

1. Clone the repo

git clone https://github.com/your-username/ai-blueprint.git

2. Environment Variables

Add the following to .env.local or via Vercel:

SUPABASE_URL

SUPABASE_ANON_KEY

OPENAI_API_KEY

STRIPE_SECRET_KEY

STRIPE_WEBHOOK_SECRET

3. Supabase Setup

Create your Supabase project

Run the schema (included in /db) to create tables: Users, Blueprints, Resources, SavedResources

Set up RLS policies (template included)

4. Deploy

Connect your GitHub repo to Vercel

Set environment variables in Vercel

Deploy 🚀

🧩 Integrations

OpenAI – GPT-4 (or GPT-3.5) to generate learning plans

Stripe – For Pro plan subscriptions

Future: Google Drive (export), YouTube API, email onboarding

🤝 Contributing

Want to help improve AI Blueprint?

Suggest a learning resource

Help tag and organize content

Share feedback or submit GitHub issues (coming soon)

📄 License

MIT License — Free to use and modify with attribution

Made with love by [@jasonweiland] 💙getaiblueprint.com
