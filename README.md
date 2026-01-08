# Project Trend 2 Post

Project Bolt is a TypeScript + React application built with Vite, Tailwind CSS, and Supabase.  
It provides tools for content generation, scheduling, and Instagram integration.

## Features

- User authentication and protected routes
- Generate AI-based content
- Schedule posts
- Instagram content management
- Supabase backend for database and serverless functions
- Tailwind CSS for responsive styling

## Tech Stack

- **Frontend:** React, TypeScript, Vite
- **Styling:** Tailwind CSS
- **Backend:** Supabase (Database, Auth, Functions)
- **Utilities:** `.bolt` AI content generation integration

## Project Structure

src/
├─ pages/ # Application pages (Home, Dashboard, Login, Register, Instagram, etc.)
├─ components/ # Reusable UI components (Layout, ProtectedRoute)
├─ services/ # API services (contentService, scheduleService)
├─ context/ # Authentication context
├─ lib/ # Supabase client setup
├─ types/ # TypeScript types

Supabase functions and migrations are in `supabase/`.

