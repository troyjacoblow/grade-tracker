# Grade Tracker

A real-time grade tracking application built with React and Convex. Track your academic progress with an easy-to-use interface.

## Features

- 📝 Record grades for different subjects
- 📅 Track test dates
- 📊 View grade history
- 🔒 Secure user authentication
- 📝 Add optional notes for each grade
- ⚡ Real-time updates

## Tech Stack

- Frontend: React + Vite
- Backend: Convex
- Styling: TailwindCSS
- Authentication: Convex Auth

## Deployment Instructions

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd grade-tracker
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Convex**
   - Create a free account at [dashboard.convex.dev](https://dashboard.convex.dev)
   - Create a new project
   - Copy your deployment URL

4. **Deploy the frontend (Vercel)**
   - Push your code to GitHub
   - Create an account at [vercel.com](https://vercel.com)
   - Import your repository
   - Add these environment variables:
     - `CONVEX_DEPLOYMENT`: Your Convex deployment URL
     - `NEXT_PUBLIC_CONVEX_URL`: Same as `CONVEX_DEPLOYMENT`
   - Deploy!

## Local Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:5173](http://localhost:5173) in your browser

## License

MIT

## Support

For issues and feature requests, please open an issue on GitHub.
