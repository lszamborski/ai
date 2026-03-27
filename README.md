# AI Chat Application

This is a Next.js TypeScript application that provides an AI chat interface, leveraging OpenAI's Chat Completions.

## Getting Started

1. Clone the repository
2. Install dependencies
   ```bash
   npm install
   ```
3. Copy the `.env.example` to `.env` and set your OpenAI API key
   ```bash
   cp .env.example .env
   ```
4. Run the development server
   ```bash
   npm run dev
   ```

## API

The application exposes an API at `/api/chat` which connects to OpenAI's Chat Completions.