# Mybrary

An early Express and EJS library-app starter. The current code connects to MongoDB and renders the home route; author and book CRUD screens have not been implemented.

## Run

Use Node.js 22.12 or newer:

```sh
npm ci
cp .env.example .env
npm run dev
```

Set `DATABASE_URL` to a MongoDB connection string. `PORT` defaults to 3000. `npm start` runs the server without watch mode.

Templates live in `views/`, routes in `routes/`, and the server entry point is `server.js`. Keep credentials in the untracked environment file.
