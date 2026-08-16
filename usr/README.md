# Kage

Kage is a production-grade AI application and orchestration system. Kage serves as the brain/orchestrator routing requests to various capabilities (Chat, Search, Memory, Attachments, Voice, Media Generation, Tools, Local AI, Cloud AI) through replaceable providers.

## Features
- **Central Orchestrator**: Routes requests intelligently across capabilities.
- **Provider-Agnostic**: Supports replacing underlying AI providers seamlessly.
- **Polished Frontend**: A pitch-black, glassmorphic UI, responsive across mobile, tablet, and desktop.
- **Capabilities**: Standard AI chat, attachments, search routing, etc.
- **Profile & Identity**: Persistent user settings and profiles.

## Setup
Run the application as a standard Flutter app:
```bash
flutter pub get
flutter run
```

## Architecture
The orchestration layer sits between the UI and the dispatchers/providers:
User -> Kage UI -> Kage Orchestrator -> Dispatcher -> Capabilities -> Providers/Local -> Kage -> User

---

## About CouldAI
This application was generated with [CouldAI](https://could.ai), an AI app builder for cross-platform apps that turns prompts into real native iOS, Android, Web, and Desktop apps with autonomous AI agents that architect, build, test, deploy, and iterate production-ready applications.
