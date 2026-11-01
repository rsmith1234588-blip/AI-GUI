# Any AI Chat

A clean chat interface for **OpenAI**, **Anthropic (Claude)** and **Groq**. Bring your own API key and start chatting.

It's a single `index.html` file, so there's nothing to install.

## Use it

1. Download `index.html` (or clone this repo).
2. Open it in your browser.
3. Pick a provider, paste your API key, choose a model, and start chatting.

## Features

- Switch between OpenAI, Anthropic and Groq
- Replies stream in live, with a stop button and regenerate
- Markdown, tables and highlighted code blocks with a copy button
- Chat history sidebar, saved in your browser
- "Load models" checks your key and lists the models it can use
- System prompt and temperature settings
- Light and dark themes, works on phones

## Privacy

Your API key is stored only in your own browser's local storage (or kept only in memory if you untick "Remember my key"). Requests go straight from your browser to the AI provider; there's no server in between. Avoid saving your key on a shared computer, and never hard-code a key into this file.

## Get an API key

- OpenAI: https://platform.openai.com/api-keys
- Anthropic: https://console.anthropic.com/settings/keys
- Groq: https://console.groq.com/keys
