# Next.js + Convex + Clerk Starter

This repository is a starter kit that wires together:

- [Next.js](https://nextjs.org) for the React application framework and routing
- [Convex](https://www.convex.dev) for the realtime backend and database
- [Clerk](https://clerk.com) for authentication and user management

Use it as a foundation for building full-stack, auth-enabled apps with a modern serverless backend.

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Copy the example environment file and fill in the Convex and Clerk keys:

   ```bash
   cp .env.example .env.local
   ```

   Update `.env.local` with your Clerk publishable/secret keys and Convex deployment info.

3. In one terminal tab, start the Convex dev service:

   ```bash
   npx convex dev
   ```

4. In a separate terminal tab, run the Next.js dev server:

   ```bash
   npm run dev
   ```

The app runs at [http://localhost:3000](http://localhost:3000). Update `app/page.tsx` (or any other route) to start customizing the starter. Convex dev tooling runs at the URL printed by `npx convex dev`.

## Additional Resources

- [Next.js Docs](https://nextjs.org/docs)
- [Convex Docs](https://docs.convex.dev)
- [Clerk Docs](https://clerk.com/docs)

When you are ready to deploy, follow the Next.js deployment guide or your hosting provider of choice; Convex and Clerk both have dedicated deployment guides in their documentation.
