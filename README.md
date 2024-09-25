## Pods: AI Generated Podcast:
A unique web app with AI-powered features like text-to-multiple-voices functionality and AI-generated images with Next.js 14 and Convex. Enabling users to create, discover, and enjoy podcasts with advanced features like text-to-audio conversion with multi-voice AI, podcast thumbnail Image generation and seamless playback.
Taken Help From 
-     https://github.com/adrianhajdin


## Tech Stack
- Next.js
- TypeScript
- Convex
- OpenAI
- Clerk
- ShadCN
- Tailwind CSS

## Features:
- 👉 Robust Authentication: Secure and reliable user login and registration system.

- 👉 Modern Home Page: Showcases trending podcasts with a sticky podcast player for continuous listening.

- 👉 Discover Podcasts Page: Dedicated page for users to explore new and popular podcasts.

- 👉 Fully Functional Search: Allows users to find podcasts easily using various search criteria.

- 👉 Create Podcast Page: Enables podcast creation with text-to-audio conversion, AI image generation, and previews.

- 👉 Multi Voice AI Functionality: Supports multiple AI-generated voices for dynamic podcast creation.

- 👉 Profile Page: View all created podcasts with options to delete them.

- 👉 Podcast Details Page: Displays detailed information about each podcast, including creator details, number of listeners, and transcript.

- 👉 Podcast Player: Features backward/forward controls, as well as mute/unmute functionality for a seamless listening experience.

- 👉 Responsive Design: Fully functional and visually appealing across all devices and screen sizes.

- and many more, including code architecture and reusability

## Quick Start

Follow these steps to set up the project locally on your machine.

Make sure you have the following installed on your machine:

- Git
- Node.js
- npm (Node Package Manager)

## Cloning the Repository

- git clone https://github.com/Diablo612/Pods.git
- cd Pods

## Installation

Install the project dependencies using npm:

-     npm install
-     yarn install

## Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

-      CONVEX_DEPLOYMENT=
-      NEXT_PUBLIC_CONVEX_URL=
-      NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
-      CLERK_SECRET_KEY=
-      NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
-      NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'
Replace the placeholder values with your actual Convex & Clerk credentials. You can obtain these credentials by signing up on the Convex and Clerk websites.

## Running the Project

-      npm run dev


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
