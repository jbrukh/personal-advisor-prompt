# Personal Advisor Prompt

A procedural prompt that interviews you, generates personalized documents about your strengths, weaknesses, and goals, then walks you through setting up a persistent AI advisor on Claude Projects or ChatGPT.

## How It Works

1. **Copy the prompt** into any AI assistant (Claude, ChatGPT, etc.)
2. **Answer the interview questions** — the AI conducts a structured conversation covering your life domains, patterns, and goals
3. **Receive two personalized documents** — a Strengths & Weaknesses profile and a Goals Outline, generated as `.md` files
4. **Name your advisor** and follow the setup instructions to install it as a persistent Claude Project or Custom GPT

Set aside 30–45 minutes. The quality of your advisor depends on the honesty and specificity of your answers.

## What You Get

- **Strengths & Weaknesses document** — 8–12 strengths and weaknesses with context, triggers, and early warning signs
- **Goals Outline** — core direction, role-based goals, daily practices, and what you're leaving behind
- **Advisor instructions** — a ready-to-paste system prompt that makes your AI hold you accountable, enforce your goals, and call out your patterns

## Files

- `personal_advisor_setup.md` — the full prompt (copy this into your AI)
- `index.html` — a single-page website for viewing and copying the prompt

## Website

The `index.html` file serves as a standalone page that renders the prompt with a copy button. It fetches `personal_advisor_setup.md` at load time and displays the version number from the file.

To run locally:

```
python3 -m http.server 8765
# then open http://localhost:8765
```

## License

MIT
