# Ping Pong Game

A simple and interactive **Ping Pong Game** built using **React, TypeScript, and Vite**. This game allows players to enjoy classic Pong gameplay with smooth animations and responsive controls.

## 🚀 Demo

Check out the live demo here: **[Play Now](https://pponggame.netlify.app/)**

## 🛠️ Tech Stack

- **React** (with Vite for fast development)
- **TypeScript** (for type safety and better developer experience)
- **CSS** (for styling and animations)

## 📂 Features

✅ **Single-Player Mode** (AI opponent)  
✅ **Smooth Animations** with `requestAnimationFrame`  
✅ **Keyboard Controls** (Arrow keys / WASD)  
✅ **Collision Detection** (Ball bounces off paddles and walls)  
✅ **Score Tracking** (Win by reaching the score limit)  
✅ **Responsive Design** (Works on all screen sizes)  
✅ **Fast Refresh with Vite**  

## 📌Installation

Follow these steps to set up the project locally:

```sh
# Clone the repository
git clone https://github.com/ManojKumar15NS/ping-pong.git

# Navigate to the project directory
cd ping-pong

# Install dependencies
yarn install  # or npm install

# Start the development server
yarn dev  # or npm run dev
```

The game should now be running at `http://localhost:5173/` by default.

## 🎮 Controls

| Key | Action |
|---|---|
| `W / Up Arrow` | Move paddle up |
| `S / Down Arrow` | Move paddle down |

## 📜 ESLint Configuration

For better code quality, the project uses ESLint with TypeScript rules. To enhance linting, update the configuration as follows:

```js
export default tseslint.config({
  languageOptions: {
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

Additionally, install `eslint-plugin-react` and update the configuration in `eslint.config.js`:

```js
import react from 'eslint-plugin-react';

export default tseslint.config({
  settings: { react: { version: '18.3' } },
  plugins: { react },
  rules: {
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
});
```

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

🎉 **Enjoy playing Ping Pong!** 🚀

