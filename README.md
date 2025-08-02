# ChizzDecorBE

Backend API for Wedding Decoration Management System

## Features

- User authentication and authorization
- Wedding decoration management
- Booking system
- Gallery management
- Payment integration with Midtrans
- File upload functionality
- Additional services management

## Tech Stack

- Node.js
- TypeScript
- Express.js
- PostgreSQL
- Supabase (for file storage)
- Midtrans (for payments)

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Set up environment variables:

   ```bash
   cp .env.example .env.local
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

## API Endpoints

- `GET /` - Health check
- `POST /auth/register` - User registration
- `POST /auth/login` - User login
- `GET /user/profile` - Get user profile
- `PUT /user/profile` - Update user profile

## Environment Variables

- `DATABASE_URL` - PostgreSQL connection string
- `JWT_SECRET` - JWT signing secret
- `SUPABASE_URL` - Supabase project URL
- `SUPABASE_ANON_KEY` - Supabase anonymous key
- `MIDTRANS_SERVER_KEY` - Midtrans server key
- `MIDTRANS_CLIENT_KEY` - Midtrans client key
