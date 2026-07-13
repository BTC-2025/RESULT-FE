# ResultHub Public Web

This repository contains the front-facing web application built explicitly for the end-users of ResultHub.

## 🎯 Purpose
The Public Web platform allows users to access the platform via their browsers rather than the mobile app. It provides a rich, dynamic social experience where users can view their feeds, search for results, view public profiles, and interact with community content.

## 📦 What It Has
- **Social Feed & Interaction:** A dynamic feed interface featuring posts, likes, and comments.
- **Search & Discovery:** Robust search capabilities for finding other users, public results, and sports data.
- **User Authentication:** Complete login, signup, and forgotten password workflows.
- **Public Profiles:** Viewable profiles displaying user stats and activity.
- **Modern UI Components:** A fully responsive, animated, and visually premium interface built with modern design principles (glassmorphism, dark mode compatibility).

## 🛠️ How It Is Built
### Tech Stack
- **Framework:** [Next.js 16](https://nextjs.org/) (App Router)
- **Library:** React 19
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **Language:** TypeScript

### Prerequisites
- [Node.js](https://nodejs.org/) (v20+ recommended)
- A running instance of the `backend-mern` API.

### Getting Started

1. **Install Dependencies**
   Navigate to the root of this folder and install the required npm packages:
   ```bash
   npm install
   ```

2. **Environment Configuration**
   Create a `.env.local` file in the root directory to point to your local backend API:
   ```env
   NEXT_PUBLIC_API_URL=http://localhost:3001/api
   ```

3. **Start the Development Server**
   Run the Next.js development server:
   ```bash
   npm run dev
   ```
   *The application will start locally at `http://localhost:3000`.*

### Available Scripts
- `npm run dev`: Starts the local development server with hot-module replacement.
- `npm run build`: Compiles the application into an optimized production build.
- `npm run start`: Starts the application in production mode (requires a prior build).
- `npm run lint`: Runs ESLint to catch syntax and styling errors.
