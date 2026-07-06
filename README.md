# 🎬 Movie Discovery App

A modern movie discovery application built with **React** that allows users to browse trending movies, search for specific titles, and maintain a personalized favorites collection using the TMDB API.

## ✨ Features

- Browse popular and trending movies
- Search movies by title
- Add and remove favorite movies
- Persist favorites using Local Storage
- Responsive and clean user interface
- Dynamic data fetched from the TMDB REST API

## 🛠 Tech Stack

- React
- Vite
- JavaScript (ES6+)
- CSS3
- React Context API
- TMDB API

## 📚 Concepts Practiced

- React Components
- React Hooks (`useState`, `useEffect`)
- Context API
- State Management
- REST API Integration
- Async/Await
- Conditional Rendering
- Local Storage

## 🚀 Getting Started

Clone the repository

```bash
git clone <repository-url>
```

Install dependencies

```bash
npm install
```

Start the development server

```bash
npm run dev
```

Create your own TMDB API key and replace:

```javascript
const API_KEY = "YOUR_TMDB_API_KEY";
```

## Future Improvements

- Movie details page
- Genre filtering
- Infinite scrolling
- Sorting by rating and release date
- Dark/Light mode
- Trailer integration
-
- # React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some Oxlint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the Oxlint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and Oxlint's TypeScript related rules in your project.
