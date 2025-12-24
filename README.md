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

Install dependencies:

```bash
npm install

![npm install output 1](./assets/npm-install-1.png)
![npm install output 2](./assets/npm-install-2.png)
![npm install output 3](./assets/npm-install-3.png)
