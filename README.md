# AI Content Generator & Structured Prompt Builder

⚡ **Live app:** https://tshepisofrominnostation.github.io/ai-content-generator/

## What it is (in simple terms)

Most people open ChatGPT, type one vague sentence, and get a mediocre result. This app fixes that. You fill in a short form what you're writing, who it's for, what tone, and the key facts and it instantly builds a professional, structured prompt you can paste into any AI tool.

The point: instead of hoping the AI understands you, you give it a clear brief the same way you'd brief a person. Better brief, better output, every time.

One-liner version: **it turns your rough idea into the perfect instructions for an AI, so the AI writes what you actually wanted.**

## Features

- **Live prompt engine** — the structured master prompt (Role / Task / Key points / Constraints / Output format) rebuilds on every keystroke as you fill in the brief
- **5 content types** — Cold Sales Email, Blog Post Outline, LinkedIn Post, Technical Project Summary, Executive Status Update, each with its own output format
- **API Generator Mode** — optional client-side API key for OpenAI, Groq or Gemini to generate content directly; falls back to a simulated preview per content type if no key is provided
- **Load Sample Data** — one click fills the form with realistic B2B/tech examples
- **Copy to clipboard** — structured prompt and generated output, with a visual "Copied!" toast
- **Prompt library** — 3 pre-built system prompt templates (cold email, blog outline, tech summary) with copy buttons
- **Accessible** — ARIA tabs and panels, labelled fields, live regions, skip link, keyboard-friendly throughout

## How to use it

1. Open the [live app](https://tshepisofrominnostation.github.io/ai-content-generator/)
2. Pick a content type, then fill in audience, tone, key points and constraints — or hit **⚡ Load Sample Data**
3. Copy the **Optimized Master Prompt** into ChatGPT, Claude, Gemini, Groq or any LLM — or switch to **API Generator Mode** and generate right in the app

## Tech stack

- Single `index.html` file — pure HTML5, vanilla JavaScript, Tailwind CSS via CDN
- Zero frameworks, zero build step, zero dependencies
- Dark theme: deep navy `#0a1628` with cyan `#22d3ee` and orange `#fb923c` accents
- API keys stay in your browser; they are never stored or sent anywhere except the provider you choose

## Run it locally

Clone the repo and open `index.html` in a browser. That's it.

```bash
git clone https://github.com/tshepisofrominnostation/ai-content-generator.git
cd ai-content-generator
# open index.html in your browser
```

## Author

**Freddy Thosago** — Full Stack & AI solutions developer, Johannesburg, South Africa

- Portfolio: https://tshepisofrominnostation.github.io/portfolio/
- GitHub: https://github.com/tshepisofrominnostation
- Email: tshepisothosago@gmail.com
