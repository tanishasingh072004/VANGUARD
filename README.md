VANGUARD | Creative Digital Collective
A premium, single-viewport creative agency landing page designed to wow users at first glance. Built using React, Vite, and Tailwind CSS (v4), this landing page features a looping high-definition video backdrop, staggered animations, interactive glassmorphic overlays, and an intelligent client-side AI Creative Assistant chatbot.

Live Demo: https://vanguard-tanisha-singh.netlify.app/

✨ Key Features
🎥 Cinematic Backdrop: A fullscreen streaming MP4 video background running on autoplay, loop, and muted state, optimized to fit the entire viewport dynamically (object-cover).
💫 Staggered Animations: Fluid entrance transitions using customized CSS @keyframes fade-up and incremental delays to load elements sequentially.
🎭 Interactive Overlays (Modals):
Portfolio Showcase: Interactive carousel showing project descriptions and high-resolution agency mockups (Luxury Packaging, Automotive Campaign, Digital Art).
Studio Manifesto: Details the creative philosophy and values.
Capabilities (Offerings): Lists agency services with premium hover effects.
Inquiry Form: Interactive contact form transitioning into a customized success state upon submission.
🤖 AI Creative Agent: A floating glassmorphic chatbot widget featuring:
Simulated natural language processing responses tailored to VANGUARD, its services, recent work, and its founder.
Interactive prompt suggestion chips.
Typing indicator animations (...) for a realistic assistant experience.
📱 Fully Responsive Layout: Built mobile-first with breakpoints for mobile, tablet (md), and desktop (lg), including a customized staggered mobile navigation overlay.
🛠️ Tech Stack
Framework: React + TypeScript
Styling: Tailwind CSS v4 & PostCSS
Build Tool: Vite
Icons: Lucide React
Deployment: Hosted on Netlify
🚀 Getting Started
Follow these steps to run the project locally on your machine.

Prerequisites
Ensure you have Node.js installed.

Installation
Clone the Repository:

bash

git clone https://github.com/YOUR_USERNAME/vanguard-landing-page.git
cd vanguard-landing-page
Install Dependencies:

bash

npm install
Start Development Server:

bash

npm run dev
Open http://localhost:5173 in your browser.

Build for Production:

bash

npm run build
This compiles the production assets into the /dist directory.

📂 Project Structure
text

├── public/                 # Static assets (Project mockups)
├── src/
│   ├── assets/             # Project assets
│   ├── App.tsx             # Main application and interactive logic
│   ├── index.css           # Tailwind v4 configuration, themes, & custom keyframe animations
│   └── main.tsx            # Application entrypoint
├── index.html              # HTML shell loading custom web fonts
├── tailwind.config.js      # Font mappings & configurations
├── postcss.config.js       # PostCSS Tailwind compiler integration
└── tsconfig.json           # TypeScript configuration
✍️ Author & Director
Curated, designed, and directed by Tanisha Singh.
