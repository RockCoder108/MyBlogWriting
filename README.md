# MyBlogWriting
MyBlogWriting is a modern, lightweight blogging platform powered by Appwrite for backend services and data management. Designed for simplicity and ease of use, it allows users to create, manage, and share blog posts through a clean and responsive interface. Ideal for developers, writers, and content creators who want a personal or small-scale blog without the overhead of building a custom backend.

# 🚀 Features
✍️ Create, edit, and delete blog posts

🗃️ Organize content with tags and categories

🔒 User authentication and session management via Appwrite

📂 Upload and manage images using Appwrite Storage

🔍 Full-text search on posts and metadata

🌓 Light/Dark mode for comfortable reading and writing

📱 Responsive UI across all devices

🧑‍💻 Role-based access control (optional)

# ⚙️ Tech Stack
Frontend: React / Vue / Svelte / [Your Frontend Framework]

Backend: Appwrite (Functions, Authentication, Database, Storage)

Database: Appwrite Database Collections

Auth: Appwrite (Email/password, OAuth providers, etc.)

Storage: Appwrite File Storage

# 📦 Getting Started
Prerequisites
Node.js installed

Appwrite instance (self-hosted or cloud at https://cloud.appwrite.io)

Appwrite project with:

Database collections (e.g., posts, users)

Storage bucket for images

Auth providers configured

# Installation
bash
Copy
Edit
git clone https://github.com/yourusername/MyBlogWriting.git
cd MyBlogWriting
npm install
Configuration
Create a .env file and add your Appwrite configuration:

env
Copy
Edit
VITE_APPWRITE_ENDPOINT=https://[HOSTNAME]/v1
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_BUCKET_ID=your_bucket_id
Running the App
bash
Copy
Edit
npm run dev


Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
