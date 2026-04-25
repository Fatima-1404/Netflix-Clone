# 🎬 Netflix Clone - Next.js Technical Implementation

A high-performance streaming interface clone built to practice modern frontend patterns, API integration, and responsive design.

## 🌟 Key Features
* **Live Data Fetching:** Integrates with the TMDB (The Movie Database) API to display real-time trending and genre-based content.
* **Modern UI/UX:** Replicates the Netflix "Browse" experience with hover effects and smooth scrolling.
* **Optimized for Speed:** Built using **Next.js** for server-side rendering and optimized image handling.
* **Fully Responsive:** Custom CSS and Bootstrap ensure a seamless experience from mobile to 4K displays.

## 🛠️ Tech Stack
* **Framework:** Next.js (React)
* **Language:** JavaScript (ES6+)
* **Styling:** CSS Modules / Bootstrap
* **Data Source:** TMDB API
* **Deployment:** Vercel

## 🧠 Technical Challenges Solved
* **Asynchronous Data:** Managed multiple concurrent API requests to populate different rows (Trending, Top Rated, etc.) without slowing down the initial page load.
* **Conditional Rendering:** Implemented logic to display movie backdrops and posters based on screen size and availability.
* **State Management:** Handled modal popups and video trailer logic for a smooth user flow.

## 🚀 How to Run
1. Clone the repo: `git clone [your-link]`
2. Install dependencies: `npm install`
3. Add your TMDB API Key to `.env.local`
4. Run the dev server: `npm run dev`
