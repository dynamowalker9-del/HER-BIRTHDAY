# Birthday Static App

A single-page birthday experience served by a small zero-dependency Node server.

## Run Locally

```bash
npm start
```

The server uses `PORT` from the environment when it is available. Locally it defaults to `3000`.

## Deploy

Use any Node-capable host such as Render, Railway, Fly.io, Heroku, or a VPS.

- Build command: none
- Start command: `npm start`
- Health check path: `/health`

Static-only hosts such as Netlify or Vercel can also serve `index.html` directly.
