SkyTrade — New Zealand's Aircraft Marketplace
SkyTrade is a modern, premium aircraft marketplace built for New Zealand's aviation community. Buy and sell fixed-wing aircraft, helicopters, jets, ultralights, and more — simple, professional, and free to browse.

What is SkyTrade?
SkyTrade connects aircraft buyers and sellers across New Zealand and beyond. Whether you're a private pilot looking to upgrade, an aviation business moving fleet, or a first-time buyer searching for your dream aircraft — SkyTrade gives you a clean, professional platform to do it.
Think Trade Me, but built specifically for aviation.

Features
For Buyers

Browse listings across all aircraft categories — Fixed Wing, Helicopter, Jet, Turboprop, Ultralight, Glider, and Agricultural
Filter by category, make/model, price, and location
Save aircraft to a personal watchlist
Contact sellers directly through the platform
Secure sign up and login with Google OAuth support

For Sellers

Free to list — no commission on private sales
Live listings the same day
Reach verified buyers across New Zealand, Australia, and internationally
Manage your listings from your personal account dashboard

Platform

Fully responsive — works on desktop and mobile
Clean, premium design built for trust and professionalism
Built-in admin portal for platform management
Real-time fee tracking and revenue dashboard for operators


Tech Stack
SkyTrade is currently built as a single-page application using:

HTML5 / CSS3 / Vanilla JavaScript — no frameworks, fast and lightweight
Google Fonts — Barlow Condensed, DM Sans, Syne
localStorage — client-side session and watchlist persistence
Blob URL — admin portal delivered without a separate server dependency


Project Structure
skytrade/
├── index.html          # Main marketplace application
├── hero-video-1.mp4    # Hero background video (helicopter)
├── hero-video-2.mp4    # Hero background video (fixed wing)
└── README.md           # This file

Deployment
SkyTrade is a static site and can be deployed to any static hosting provider.
Recommended hosts:

Cloudflare Pages — fastest, free, no limits
GitHub Pages — free, simple
Vercel — free hobby tier

To deploy:

Rename skytrade.html to index.html
Place index.html, hero-video-1.mp4, and hero-video-2.mp4 in the same folder
Upload the folder to your chosen host


All three files must be in the same directory — the HTML references the videos by relative path.


Admin Portal
SkyTrade includes a built-in admin portal accessible from the main navigation bar.
Default credentials:
Username: admin
Password: skytrade2025

Change these credentials before going live in production.

The admin portal provides:

Full listings management (approve, suspend, remove)
Customer database overview
Fee and revenue tracking (2.5% platform fee per sale)
Platform settings and configuration


Roadmap
The current version is a front-end prototype. Planned upgrades include:

 Supabase backend integration (real database, auth, file storage)
 Stripe payment integration for platform fee collection
 Photo uploads on listings (up to 20 images)
 Listing valuation tool
 Email notifications via Resend
 Saved search alerts
 Verified seller badges
 Mobile app (React Native)


About
SkyTrade is built and operated in New Zealand. The platform is designed to serve the NZ aviation community with a premium, no-BS marketplace that feels modern and trustworthy.
For enquiries: admin@skytrade.co.nz

SkyTrade — Buy & Sell with Confidence.
