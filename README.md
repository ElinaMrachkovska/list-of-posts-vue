# Vue Dynamic List of Posts

Simple single-page app to view, create, edit and delete posts with per-post comments in a sidebar.

Demo: https://elinamrachkovska.github.io/list-of-posts-vue/

Short description
- The app shows a posts table for the current user, allows creating new posts, opening a post in a sidebar to view/edit/delete it and its comments, and adding/removing comments.

Technologies & frameworks
- Vue.js
- Vite (development build tool)
- Bulma (CSS framework)
- Fetch API / Axios (HTTP requests)
- Mate API (Posts and Users) — https://mate-academy.github.io/fe-students-api
- Optional: pnpm / npm / yarn (package manager)

Key features
- List posts for the logged-in user
- Create, edit and delete posts
- Sidebar view with post details and comments
- Add and delete comments (optimistic deletion)
- Loading and error states, simple form validation
- Responsive UI styled with Bulma

Quick start
1. Install dependencies:
   - pnpm install OR npm install OR yarn
2. Run dev server:
   - pnpm dev OR npm run dev OR yarn dev

Notes
- The app expects the Mate API to be available for posts, users and comments.
- Configure publicDir or API settings in