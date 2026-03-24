# Recipe Remix

AI-powered app that transforms any recipe screenshot based on cuisine, dietary restrictions, and appliances.

## Features

- **Upload** – Drag & drop or click to upload a recipe screenshot
- **Cuisine** – Transform to Italian, Indian, Thai, Mexican, Japanese, and more
- **Dietary** – Apply Vegan, Keto, or Gluten-Free restrictions
- **Appliance** – Adapt instructions for Oven, Air Fryer, or Stovetop
- **Copy & Download** – Export your remixed recipe as text

## Setup

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Add your OpenAI API key**
   ```bash
   cp .env.example .env.local
   ```
   Edit `.env.local` and add your key:
   ```
   OPENAI_API_KEY=sk-your-api-key-here
   ```

3. **Run locally**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000)

## Deploy to Vercel

1. Push your code to GitHub
2. Import the project in [Vercel](https://vercel.com)
3. Add `OPENAI_API_KEY` in Project Settings → Environment Variables
4. Deploy

## Tech Stack

- **Frontend:** Next.js 14 (App Router) + Tailwind CSS
- **Backend:** Next.js API Routes
- **AI:** OpenAI GPT-4o (vision + text)
