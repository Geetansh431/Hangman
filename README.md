# Hangman Game

A modern implementation of the classic Hangman word guessing game built with React, TypeScript, and Vite. This interactive web application provides an engaging way to test your vocabulary and word-guessing skills.

## Features

- 🎮 Classic Hangman gameplay mechanics
- 🎨 Visual hangman drawing that progressively appears with incorrect guesses
- ⌨️ Interactive keyboard for letter input
- 🔄 Automatic word selection from a curated word list
- 🎯 Win/lose state detection
- 📱 Responsive design for various screen sizes

## Tech Stack

- React 19
- TypeScript
- Vite
- CSS Modules

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository
2. Navigate to the project directory
3. Install dependencies:
```bash
npm install
```

### Development

To start the development server:
```bash
npm run dev
```

### Building for Production

To create a production build:
```bash
npm run build
```

### Preview Production Build

To preview the production build locally:
```bash
npm run preview
```

## How to Play

1. The game starts with a random word and an empty gallows
2. Click letters on the virtual keyboard or use your physical keyboard to guess letters
3. Correct guesses reveal the letter in the word
4. Incorrect guesses add a part to the hangman drawing
5. Win by guessing all letters in the word
6. Lose if the hangman drawing completes (6 incorrect guesses)
7. Press Enter to start a new game

## Development

This project uses ESLint for code quality. To run the linter:
```bash
npm run lint
```
