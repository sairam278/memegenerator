# Meme Generator

A React application that lets you create custom memes by adding top and bottom text over randomly fetched meme images.

## Features

- Fetches 100+ popular meme templates from the [Imgflip API](https://api.imgflip.com/get_memes)
- Add custom top and bottom text to any meme
- Randomize the meme image with a single button click
- Live preview updates as you type

## Tech Stack

- React 19
- Vite
- Imgflip API

## Getting Started

```bash
cd memegenerator
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure

```
memegenerator/
├── src/
│   ├── Components/
│   │   ├── Header.jsx   # App header with title
│   │   └── Main.jsx     # Meme editor (text inputs + image display)
│   ├── assets/
│   │   └── meme.jpg     # Default meme placeholder
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
└── package.json
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |
