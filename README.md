# React Tic-Tac-Toe

A classic Tic-Tac-Toe game built with React, focusing on clean state management and derived state architecture.

## ✨ Features

- Turn-based Tic-Tac-Toe gameplay
- Single source of truth using move history
- Derived active player (no redundant state)
- Game log showing move history
- Clean and modular component structure

## 🧠 State Management Approach

This project avoids unnecessary state.

- The **only state** stored is the game turn history.
- The active player is **derived from previous turns**, not stored separately.
- The game board is reconstructed from the move history on each render.

This approach follows React best practices:
> If a value can be derived from existing state, it should not be stored as separate state.

## 🛠 Tech Stack

- React
- Vite
- JavaScript (ES6+)
- CSS

## ▶️ Getting Started
## 📦 npm install

![npm install output 1](https://github.com/user-attachments/assets/98a5dffa-8e9d-4180-a7a1-5c6cee48cc9d)

![npm install output 2](https://github.com/user-attachments/assets/5027c352-b9ff-4c00-b6f7-909c31d1de74)

![npm install output 3](https://github.com/user-attachments/assets/7ede4d05-d9f3-4d0a-9acd-5a2c13038eef)

