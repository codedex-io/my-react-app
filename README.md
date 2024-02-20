# Codédex + Vite

![Social Post Demo GIF](/src/social-post-react.gif)

**Important:** This is a templatae specifically made for our React course at Codédex. It was curated from the default boilerplate code you'd typically see in a freshly-created React app a la Vite.

This template provides a minimal setup to get React working in Vite with [hot module replacement (HMR)](https://vitejs.dev/guide/features.html#hot-module-replacement) and some ESLint rules.

## Launching the App

To run this application, make sure you are in the root directory and you've run the following:

```terminal
npm install
npm run dev
```

You should now be able to access a `localhost` URL appear on the command line (e.g., ` http://localhost:5173/`).

## Structure

Below are the main files used in a Vite React app:

- **src/**
  - **App.jsx** - The code for the `<App>` component.
  - **index.css** - The base styles for the React app.
- **index.html** - The place where the root of the React app (i.e., `<div id="root"></div>`)
- **package-lock.json** - A confirmation of the outside code used in `package.json` and their versions.
- **package.json** - A running list of the outside code used to make this app run, including `react`, `react-dom`, and `vite`.
- **READEME.md** - The file you are reading right now.
- **vite.config.js** - This repo was originally a default Vite React app, and these are its settings.

