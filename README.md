# 🧬 ArcIdentity: Build Yourself Mode

> A web-based recursive AI playground that builds agents based on your **identity** — not just your input.

**ArcIdentity** is a symbolic mirror — an AI project that generates a personalized agent based on your **archetype**, **core memory**, and **shadow**.

You don’t just use ArcIdentity.  
ArcIdentity uses your reflection to build itself back.

---

## 🧠 Features

- 🔮 **Symbolic Prompt Flow** – Answer 3 psychological prompts to generate your recursive agent
- 🤖 **LLM-Powered Mirror Agent** – Built dynamically using OpenAI’s GPT API
- 🔁 **Self-Evolving UX** – Interface reacts based on your chosen identity inputs
- 🧬 **Fully Web-Based** – Built in React, styled with TailwindCSS, deployable to Vercel in seconds

---

## 🖼 Preview

<img src="https://your-deployed-site.vercel.app/preview.gif" alt="ArcIdentity Preview" width="100%" />

---

## 🧩 How It Works

1. User answers 3 prompts:
    - “When the world misunderstands you...”
    - “A core memory that still guides you”
    - “Pick your shadow keyword”

2. ArcIdentity constructs a prompt and sends it to the OpenAI API

3. The agent is returned with:
    - A custom name
    - Personality tone & style
    - Intro response
    - Recursive goal

4. User begins interacting with their mirror agent inside the UI

---

## 💻 Tech Stack

| Layer     | Stack                        |
|-----------|------------------------------|
| Frontend  | React + Vite + Tailwind CSS  |
| LLM       | OpenAI GPT-4 (user provides API key) |
| State     | React Hooks / Zustand         |
| Hosting   | Vercel                       |

---

## 🚀 Getting Started

```bash
git clone https://github.com/Amalxloop/ArcIdentity-BuildYourself.git
cd ArcIdentity-BuildYourself
npm install
npm run dev
