# PulseCheck - Team Analytics Dashboard

PulseCheck is a lightweight dashboard that tracks your dev team's collaborative energy through commits, PRs, messages, and blockers — visualized as team pulse. It helps surface early signals of burnout, overload, or disengagement.

## Features

- 🔐 Secure authentication with email/password
- 👥 Team management with invite system
- 📊 Activity visualization with charts and graphs
- 🔄 Real-time activity tracking
- 📈 Team and individual performance metrics
- 🚫 Blocker tracking and alerts
- 😊 Team morale monitoring

## Tech Stack

- Next.js 13 with App Router
- TypeScript
- Prisma (SQLite)
- NextAuth.js
- Tailwind CSS
- Tremor (Charts)

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up the database:
   ```bash
   npx prisma generate
   npx prisma db push
   ```
4. Create a `.env.local` file with:
   ```
   NEXTAUTH_SECRET=your-secret-key
   NEXTAUTH_URL=http://localhost:3000
   ```
5. Run the development server:
   ```bash
   npm run dev
   ```

Open [http://localhost:3000](http://localhost:3000) to see the application.

## Project Structure

- `/src/app` - Next.js 13 app router pages and layouts
- `/src/app/api` - API routes for authentication and team management
- `/prisma` - Database schema and migrations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
