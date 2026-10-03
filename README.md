# Nexora Store — Thiranex Task 5

A responsive e-commerce product catalog built with **React + Vite**.

## Features

- Modular React components
- Client-side routing with React Router
- Product search and category filtering
- Product detail pages
- Add-to-cart and quantity controls
- Cart persistence using LocalStorage
- Responsive mobile-first layout
- Production build with Vite minification
- Vercel SPA rewrite included for nested routes

## Run locally

```bash
npm install
npm run dev
```

Then open the local Vite URL.

## Production build

```bash
npm run build
npm run preview
```

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. Open Vercel and import the GitHub repository.
3. Framework preset: **Vite**.
4. Build command: `npm run build`
5. Output directory: `dist`
6. Deploy.
7. The included `vercel.json` handles React Router routes.

## Suggested GitHub repository

**thiranex-task-5**

## Suggested description

**Full-stack deployment and project architecture capstone — responsive Nexora e-commerce catalog built with React, Vite and client-side routing.**

## Project structure

```text
thiranex-task-5/
├── src/
│   ├── components/
│   ├── data/
│   ├── pages/
│   ├── App.jsx
│   ├── main.jsx
│   └── styles.css
├── index.html
├── package.json
├── vite.config.js
├── vercel.json
└── README.md
```
