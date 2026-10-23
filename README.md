# NoteX — Notes App

A simple, clean notes app built with **React** and **Vite**. Write a note with a title and description, see it appear instantly as a card, and delete it with one click. Your notes are saved in the browser's `localStorage`, so they're still there when you come back.

## Features

- **Create notes** with a title and description
- **Delete notes** with the trash icon on each card
- **Saved automatically** in `localStorage` — no account or backend needed
- **Card layout** for browsing all your notes at a glance

## Tech Stack

- [React 19](https://react.dev/)
- [Vite 7](https://vite.dev/)
- [React Icons](https://react-icons.github.io/react-icons/)
- ESLint

## Getting Started

You'll need [Node.js](https://nodejs.org/) installed.

```bash
# Clone the repository
git clone https://github.com/WIZARD696/Notes-React-App.git
cd Notes-React-App

# Install dependencies
npm install

# Start the development server
npm run dev
```

Then open the local URL shown in the terminal (usually http://localhost:5173).

## Scripts

| Command           | Description                          |
| ----------------- | ------------------------------------ |
| `npm run dev`     | Start the development server         |
| `npm run build`   | Build for production into `dist/`    |
| `npm run preview` | Preview the production build locally |
| `npm run lint`    | Run ESLint                           |

## Project Structure

```
├── components/
│   ├── Card.jsx      # A single note card with a delete button
│   └── Navbar.jsx    # Top navigation bar
├── src/
│   ├── App.jsx       # Note form, notes list and localStorage logic
│   ├── App.css
│   ├── index.css
│   └── main.jsx      # App entry point
├── index.html
└── vite.config.js
```
