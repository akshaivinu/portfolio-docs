# Netflix Clone

<div style="margin-bottom: 20px;">
  <span class="badge badge-primary">React</span>
  <span class="badge badge-primary">Tailwind CSS</span>
  <span class="badge badge-success">Node.js</span>
  <span class="badge">MongoDB</span>
  <span class="badge">TMDB API</span>
</div>

A full-stack, responsive streaming platform clone that mimics the core features and aesthetic of Netflix.

## 🎯 Project Goals

The objective of this project primarily revolved around mastering complex UI states, handling large sets of external media data efficiently, and creating a pixel-perfect dark-mode interface.

## ✨ Key Features

- **Authentication:** Secure email/password login and registration mapped to a MongoDB backend.
- **Dynamic Content:** Fetched real-time movie and TV show data using the TMDB API.
- **Interactive UI:** Hover states, horizontal scrolling rows, and hero banner trailers.
- **My List:** Ability for users to save their favorite shows to a personalized list tied to their specific account.

## 🛠️ Technical Challenges

### Handling Horizontal Image Carousels
Replicating Netflix's smooth scrolling behavior required custom hook implementation to track scroll position and handle responsive breakpoints dynamically without jank or scrollbar artifacting.

### Global State Management
Managing the user's "My List" across different components was handled efficiently using React Context and custom hooks, ensuring that when an item was added, the UI updated instantly across all views.

## 🎨 UI/UX Details

- **Micro-interactions:** Subtle scaling effects on movie posters during hover interactions.
- **Performant Images:** Implemented lazy loading for images to ensure the initial load time is blazingly fast despite loading dozens of high-resolution posters at once.
- **Gradient Overlays:** Applied precise CSS gradients to ensure textual elements and UI buttons remain highly readable against random, dynamic background hero images.
