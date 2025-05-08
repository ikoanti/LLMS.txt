
# LLMS.txt

A simple and transparent initiative to give website owners control over access by Large Language Models (LLMs) and AI crawlers.

Inspired by [llmstxt.org](https://llmstxt.org/), this repository provides a community-maintained `robots.txt` format tailored to manage AI-specific bots like ChatGPT, Google Gemini, Claude, and others.

---

## ✨ What is LLMS.txt?

LLMS.txt is not a new protocol or standard. It's a focused use of the existing `robots.txt` file to help website owners communicate their preferences to AI crawlers.

It’s part of an ongoing conversation around **consent, transparency, and the future of AI training data**.

---

## 🧾 Use Cases

- ✅ **Allow AI crawlers** to access your public content
- ❌ **Disallow LLMs** from scraping your site
- ⚙️ **Customize rules** for specific bots

---

## 📄 Templates

### Disallow All LLMs

```txt
User-agent: GPTBot
Disallow: /

User-agent: Google-Extended
Disallow: /

User-agent: ClaudeBot
Disallow: /

User-agent: CCBot
Disallow: /

User-agent: ChatGPT-User
Disallow: /

User-agent: anthropic-ai
Disallow: /

User-agent: cohere-ai
Disallow: /

User-agent: FacebookBot
Disallow: /

User-agent: Applebot
Disallow: /
