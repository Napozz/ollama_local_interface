## Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Ollama model

In `/src/app/api/chat/routes.ts` select your ollama model from [repo](https://ollama.com/library).

```typescript
const result = await streamText({
  model: ollama("llama3.1"),
  messages,
});
```
