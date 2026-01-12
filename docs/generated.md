## Commit Docs Phase 1 Overview

This video explains the backend architecture of the CommitDox project, which consists of three services: Whisper, FIA, and the main backend API.

- Whisper Service runs on Port 7,001 and transcribes videos into text.
- FIA Service runs on Port 7,02 and converts transcripts into structured documentation sections in JSON format.
- The main backend API runs on Port 3000 and handles video uploads, transcriptions, and documentation generation.
- The pipeline processes one job at a time to avoid resource contention.
- Phase one does not support concurrency, retries, or streaming.

```
Whisper Service runs on Port 7,001
```

```
FIA Service runs on Port 7,02
```

```
Main backend API runs on Port 3000
```

