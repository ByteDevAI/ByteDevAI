# Byte

**An AI API that costs pennies.** OpenAI-compatible: change two lines, keep your code.

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://api.bytedev.co.uk/v1",
    api_key="byte_…",
)
r = client.chat.completions.create(
    model="byte-chat",
    messages=[{"role": "user", "content": "hello"}],
)
```

| Model | What | Price |
|---|---|---|
| `byte-chat` | Chat completions + streaming | 5p / 50p per 1M tokens in / out |
| `byte-image` | Image generation | 0.5p per image |

- **Works with what you already use:** the OpenAI SDKs, LangChain, Continue, Aider, OpenWebUI.
- **Prepaid, no subscription.** Top up on Ko-fi; it stops at £0 and never overspends.
- **Honest:** a side project on its own hardware, best-effort, no uptime guarantee. Great for bots,
  side projects and scripts; not for anything mission-critical.

**[Get a key →](https://api.bytedev.co.uk)**

---

Also from Byte: [ByteChat](https://chat.bytedev.co.uk) · [Discord bot](https://discord.com/oauth2/authorize?client_id=1483232329404121160) · [Vote on top.gg](https://top.gg/bot/1483232329404121160/vote) · [bytedev.co.uk](https://bytedev.co.uk)

<sub>Commits co-authored by Byte were written with Byte's coding tools.</sub>
