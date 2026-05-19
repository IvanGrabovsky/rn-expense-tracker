# rn-expense-tracker

Expense tracker app (React Native / Expo).

## How to run the app

1. Install dependencies:

```bash
npm install
```

2. Start the Expo development server:

```bash
npm start
```

3. Run on a specific platform (optional):

```bash
npm run android
npm run ios
npm run web
```

## Backend configuration

This app loads and saves expenses through a remote backend. Before running the app, open `utils/http.js` and set `BACKEND_URL` to a **valid Firebase Realtime Database URL** for your project (see the comment in that file). Without a working URL, fetch, create, update, and delete requests will fail.

If you need help setting this up, contact the author at [ivan.grabovsky.ua@gmail.com](mailto:ivan.grabovsky.ua@gmail.com).
