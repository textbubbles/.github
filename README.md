<p align="center">
  <img src="https://raw.githubusercontent.com/textbubbles/.github/main/logo.png" alt="TextBubbles" width="120" />
</p>

<h1 align="center">TextBubbles</h1>
<p align="center"><strong>iMessage API for developers. Send blue bubbles at scale.</strong></p>

<p align="center">
  <a href="https://textbubbles.com">Website</a> •
  <a href="https://docs.textbubbles.com">Documentation</a> •
  <a href="https://github.com/textbubbles/js">SDK</a> •
  <a href="https://status.textbubbles.com">Status</a>
</p>

---

## What is TextBubbles?

TextBubbles provides a simple REST API to send iMessages, SMS, reactions, and rich media programmatically. Perfect for notifications, customer support, and marketing automation.

## Quick Start

```bash
npm install @textbubbles/js
```

```typescript
import { TextBubblesClient } from "@textbubbles/js";

const client = new TextBubblesClient({
  apiKey: process.env.TEXTBUBBLES_API_KEY
});

await client.messages.send({
  to: "+14155551234",
  content: { text: "Hello from TextBubbles! 💬" },
  effect: "confetti"
});
```

## Features

| Feature | Description |
|---------|-------------|
| 💬 **iMessage & SMS** | Auto-fallback to SMS for Android |
| 📸 **Rich Media** | Images, carousels, voice memos |
| ⏰ **Scheduled Messages** | Send later with precision |
| 💳 **Payment Requests** | Request Apple Cash via iMessage |
| 👥 **Group Chats** | Create and manage conversations |
| 🔔 **Webhooks** | Real-time delivery & read receipts |
| ❤️ **Reactions** | Tapback reactions (love, like, etc.) |
| ✨ **Effects** | Confetti, fireworks, lasers, and more |

## Repositories

| Repository | Description |
|------------|-------------|
| [textbubbles/js](https://github.com/textbubbles/js) | Official JavaScript/TypeScript SDK |
| [textbubbles/docs](https://github.com/textbubbles/docs) | API Documentation |
| [textbubbles/landing](https://github.com/textbubbles/landing) | textbubbles.com website |

---

<p align="center">Built with 💙</p>
