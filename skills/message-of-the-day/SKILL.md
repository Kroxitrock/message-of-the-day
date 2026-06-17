---
name: message-of-the-day
description: Give a concise message of the day when the user asks for a daily note, daily message, morning note, intention, focus prompt, or "message of the day".
---

# Message of the Day

When this skill is triggered, respond with a short, useful message for the current day.

## Response Shape

Use this format:

```text
Message of the day for <weekday, Month D, YYYY>

Theme: <3-6 word theme>

<Two or three warm, practical sentences. Keep the tone grounded and useful.>

Tiny action: <one concrete action the user can do in under five minutes>
```

## Guidance

- Use the current date from the conversation or system context.
- Make the message feel fresh rather than generic.
- Keep it under 120 words.
- Avoid grand claims, horoscopes, superstition, or pretending to know private facts about the user.
- If the user asks for a specific style, mood, or topic, adapt the message while preserving the concise format.
