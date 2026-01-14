## Backend Architecture of Commit Docs

The backend architecture of Commit Docs is built using Node.js, Fastify, and TypeScript. It consists of three services: Whisper, Fi, and the main API.

- Whisper service runs on Port 7001 and transcribes uploaded videos into text.
- Fi service runs on Port 7002 and converts transcripts into structured JSON documentation.
- The main API runs on Port 3000 and orchestrates the pipeline.

```
Function add(a, b) return a + b.
```

