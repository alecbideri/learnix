# Learnix

Learnix is a modern web application built with Next.js 15, designed to provide an interactive learning experience with AI companions.

## Features

- **AI Companions**: Interactive AI-powered companions to guide your learning journey.
- **Learning Journey Tracking**: Track your progress and achievements.
- **Subscription Management**: Manage your subscription tiers and access.
- **Secure Authentication**: User authentication and management powered by Clerk.

## Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **Authentication**: [Clerk](https://clerk.com/)
- **Database**: [Supabase](https://supabase.com/)
- **Monitoring**: [Sentry](https://sentry.io/)
- **AI/Voice**: [Vapi.ai](https://vapi.ai/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/), [Lucide React](https://lucide.dev/)
- **Design**: Brutalism-inspired aesthetics
- **Animations**: [Lottie React](https://lottiefiles.com/), [TW Animate CSS](https://www.npmjs.com/package/tw-animate-css)

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm, yarn, or pnpm

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd learnix
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. Set up environment variables:

   Create a `.env.local` file in the root directory and add the necessary environment variables for Clerk, Supabase, Sentry, and Vapi.ai.

### Running the Development Server

Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `app/`: Application routes and pages (App Router).
- `components/`: Reusable UI components.
- `constants/`: Constant values and configuration.
- `lib/`: Utility functions and libraries.
- `public/`: Static assets.
- `types/`: TypeScript type definitions.

## Scripts

- `npm run dev`: Starts the development server with Turbopack.
- `npm run build`: Builds the application for production.
- `npm run start`: Starts the production server.
- `npm run lint`: Runs ESLint to check for code quality issues.
