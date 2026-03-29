# TextBubbles 💬

**iMessage API for developers. Send blue bubbles at scale.**

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

## Links

- 🌐 [Website](https://textbubbles.com)
- 📚 [Documentation](https://docs.textbubbles.com)
- 📦 [JavaScript SDK](https://github.com/textbubbles/js)
- 🔌 [API Reference](https://docs.textbubbles.com/api-reference)

## Features

- 💬 **iMessage & SMS** - Auto-fallback to SMS for Android
- 📸 **Rich Media** - Images, carousels, voice memos
- ⏰ **Scheduled Messages** - Send later with precision
- 💳 **Payment Requests** - Request Apple Cash via iMessage
- 👥 **Group Chats** - Create and manage conversations
- 🔔 **Webhooks** - Real-time delivery & read receipts
- ❤️ **Reactions** - Send tapback reactions (love, like, etc.)
- ✨ **Effects** - Confetti, fireworks, lasers, and more

---

*Built with 💙 by the TextBubbles team*
