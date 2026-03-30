<div align="center">

# 💬 TextBubbles

### The iMessage & SMS API Built for Developers

[![Website](https://img.shields.io/badge/Website-textbubbles.com-007AFF?style=flat-square)](https://textbubbles.com)
[![Docs](https://img.shields.io/badge/Docs-docs.textbubbles.com-007AFF?style=flat-square)](https://docs.textbubbles.com)
[![npm](https://img.shields.io/npm/v/@textbubbles/js?style=flat-square&color=007AFF)](https://www.npmjs.com/package/@textbubbles/js)

</div>

---

**TextBubbles** is a messaging API that lets you send iMessages programmatically with automatic SMS fallback for Android users. One API, universal reach.

## ✨ Features

- 💬 **iMessage & SMS** — Blue bubbles for Apple users, SMS fallback for everyone else
- 📸 **Rich Media** — Send images, videos, voice memos, and link previews
- ❤️ **Reactions** — Add tapback reactions to messages
- 🎉 **Effects** — Confetti, balloons, fireworks, and more
- 👥 **Group Chats** — Create and manage group conversations
- 🔔 **Webhooks** — Real-time delivery receipts and reply tracking
- ⏰ **Scheduling** — Send messages at the perfect time

## 🚀 Quick Start

```bash
npm install @textbubbles/sdk
```

```typescript
import { TextBubbles } from '@textbubbles/sdk';

const tb = new TextBubbles({ apiKey: 'your-api-key' });

await tb.messages.send({
  to: '+1234567890',
  text: 'Hello from TextBubbles! 💬',
});
```

## 📦 Repositories

| Repository | Description |
|------------|-------------|
| [**js**](https://github.com/textbubbles/js) | Official TypeScript/JavaScript SDK |
| [**docs**](https://github.com/textbubbles/docs) | API documentation (docs.textbubbles.com) |
| [**landing**](https://github.com/textbubbles/landing) | Marketing site (textbubbles.com) |

## 📚 Documentation

- [Getting Started](https://docs.textbubbles.com/getting-started)
- [API Reference](https://docs.textbubbles.com/api)
- [SDK Guide](https://docs.textbubbles.com/sdk)
- [Webhooks](https://docs.textbubbles.com/webhooks)

## 💬 Community

- [Discord](https://discord.gg/textbubbles)
- [Twitter](https://twitter.com/textbubbles)

---

<div align="center">
  <sub>Built with 💙 for developers who ship.</sub>
</div>
