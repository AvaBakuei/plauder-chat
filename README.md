# Plauder

An AI chat web app: talk to an OpenAI model, keep your conversation history and pick up old chats where you left off.

> Work in progress. This is the web rebuild of [cli-chat](https://github.com/AvaBakuei/cli-chat), a terminal chat client written in Python.

## Tech stack

- [Next.js](https://nextjs.org) (App Router) and React
- TypeScript
- Tailwind CSS
- ESLint and Prettier

## Getting started

Requirements: Node.js (version in `.nvmrc`) and an OpenAI API key.

```bash
npm install
cp .env.example .env.local   # then add your OPENAI_API_KEY
npm run dev
```

Open http://localhost:3000.

## Scripts

| Script                 | What it does                     |
| ---------------------- | -------------------------------- |
| `npm run dev`          | Start the development server     |
| `npm run build`        | Build for production             |
| `npm run lint`         | Run ESLint                       |
| `npm run format`       | Format all files with Prettier   |
| `npm run format:check` | Check formatting without changes |
