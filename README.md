# 🎮 Hangman Game

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 📖 About The Project

A classic **Hangman** word guessing game built with modern web technologies. Test your vocabulary and reasoning skills by guessing the hidden word one letter at a time. With an intuitive interface and smooth animations, this game provides an engaging experience for players of all ages.

## ✨ Key Features

- 🎯 **Interactive Gameplay** - Click letters to make your guess
- 🎨 **Dynamic Hangman Drawing** - Visual feedback with SVG animations
- ⌨️ **Keyboard Support** - Use physical keyboard for quick play
- 📱 **Responsive Design** - Play seamlessly on any device
- 🔄 **New Game Option** - Restart anytime with a fresh word
- 🎲 **Random Word Selection** - Diverse word pool from JSON data
- ✅ **Win/Lose Detection** - Clear game state indicators
- 🎪 **Visual Feedback** - Color-coded letters (correct/incorrect/unused)

## 🛠️ Built With

### Core Technologies

- **[React](https://react.dev/)** (v18.3.1) - UI component library
- **[TypeScript](https://www.typescriptlang.org/)** (v5.6.2) - Type-safe JavaScript
- **[Vite](https://vite.dev/)** (v6.0.1) - Next-generation frontend tooling

### Development Tools

- **ESLint** - Code quality and consistency
- **TypeScript ESLint** - TypeScript-specific linting
- **Vite React Plugin** - Fast refresh and optimization
- **React Hooks** - useState, useEffect, useCallback

## 🎯 Game Features

### Gameplay Mechanics

- **Word Display** - Hidden letters revealed as you guess correctly
- **Virtual Keyboard** - On-screen letter buttons for easy interaction
- **Physical Keyboard** - Full keyboard support for faster gameplay
- **Hangman Drawing** - Progressive drawing with each incorrect guess
- **6 Lives** - Six chances to guess the word correctly
- **Win/Lose States** - Clear victory or defeat messages

### Visual Elements

- **SVG Graphics** - Smooth, scalable hangman illustration
- **Color Coding**
  - 🔵 Blue - Correct letter
  - 🔴 Red - Incorrect letter
  - ⚫ Black - Available letter
- **Responsive Layout** - Adapts to different screen sizes
- **Clean UI** - Minimalist design focusing on gameplay

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/khamzaevasad/hangman.git
   cd hangman
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:5173
   ```

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## 📦 Project Structure

```
hangman/
├── public/
│   └── logo.png
├── src/
│   ├── App.css
│   ├── App.tsx
│   ├── HangmanDrawing.tsx
│   ├── HangmanWord.tsx
│   ├── index.css
│   ├── Keyboard.module.css
│   ├── Keyboard.tsx
│   ├── main.tsx
│   └── wordList.json
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
└── vite.config.ts
```

## 🎮 How to Play

1. **Start the Game** - A random word is selected automatically
2. **Guess Letters** - Click on-screen buttons or use your keyboard
3. **Watch Progress** - Correct letters appear in the word, incorrect ones draw the hangman
4. **Win or Lose**
   - Win: Guess all letters before 6 incorrect attempts
   - Lose: Complete the hangman drawing (6 wrong guesses)
5. **Play Again** - Click "Refresh - Try again" to start a new game

## 🔧 Component Architecture

### Main Components

- **App.tsx** - Main game logic and state management
- **HangmanDrawing.tsx** - SVG-based hangman illustration
- **HangmanWord.tsx** - Word display with letter reveals
- **Keyboard.tsx** - Interactive letter selection interface

### State Management

- **wordToGuess** - Current target word
- **guessedLetters** - Array of attempted letters
- **Derived States** - Win/lose conditions, incorrect letters

## 📝 Technologies Breakdown

### TypeScript Benefits

- Type safety for game logic
- Better IDE support and autocomplete
- Catch errors during development
- Improved code maintainability

### React Features Used

- Functional components
- React Hooks (useState, useEffect, useCallback)
- Component composition
- Conditional rendering
- Event handling

### Vite Advantages

- Lightning-fast HMR (Hot Module Replacement)
- Optimized production builds
- Modern ES modules support
- Plugin ecosystem

## 👨‍💻 Author

**KhamzaevAsad** - Frontend Developer

- **Email** - xamzayevasad4422@gmail.com
- **GitHub** - [@khamzaevasad](https://github.com/khamzaevasad)
- **Location** - Chuncheon, South Korea

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- React documentation and community
- TypeScript team for excellent tooling
- Vite for blazing-fast development experience

---

**Enjoy the game! 🎉**
