Introduction
  
A cutting-edge AI SaaS platform that enables users to create, discover, and enjoy podcasts with advanced features like text-to-audio conversion with multi-voice AI, podcast thumbnail Image generation and seamless playback.

Tech Stack
 
  
  Next.js
  TypeScript
  Convex
  OpenAI
  Clerk
  ShadCN
  Tailwind CSS

Features 
 
  
  Robust Authentication: Secure and reliable user login and registration system.
  Modern Home Page: Showcases trending podcasts with a sticky podcast player for continuous listening.
  Discover Podcasts Page: Dedicated page for users to explore new and popular podcasts.
  Fully Functional Search: Allows users to find podcasts easily using various search criteria.
  Create Podcast Page: Enables podcast creation with text-to-audio conversion, AI image generation, and previews.
  Multi Voice AI Functionality: Supports multiple AI-generated voices for dynamic podcast creation.
  Profile Page: View all created podcasts with options to delete them.
  Podcast Details Page: Displays detailed information about each podcast, including creator details, number of listeners, and transcript.
  Podcast Player: Features backward/forward controls, as well as mute/unmute functionality for a seamless listening experience.
  Responsive Design: Fully functional and visually appealing across all devices and screen sizes.


Quick Start

  Prerequisites
  
  Make sure you have the following installed on your machine:
 
   Git
   Node.js
   npm (Node Package Manager)


Installation

 Install the project dependencies using npm:
 
  npm install

Set Up Environment Variables

 CONVEX_DEPLOYMENT=
 
 NEXT_PUBLIC_CONVEX_URL=
 
 NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
 
 CLERK_SECRET_KEY=
 
 NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
 
 NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'

Replace the placeholder values with your actual Convex & Clerk credentials. You can obtain these credentials by signing up on the Convex and Clerk websites.

Running the Project
 npm run dev

Open http://localhost:3000 in your browser to view the project.
