## PhiBase Service for Whisper Transcripts

A fast API service that exposes a structure endpoint used by the node backend. A new PhiBase service has been added that converts whisper transcripts into structured documentation sections.

- Automatically generates documentation PRs from walkthrough videos.
- Main file affected is docks generated.md, containing a summary and bullet points derived from the video.
- Vague walkthroughs may produce vague documentation.

