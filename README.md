# n8n-ai-assistant

# 🎙️ Automated AI Podcast Generator (n8n Workflow)

An end-to-end automated workflow built using **n8n** and **Google Gemini** that takes a topic, article, or raw text input, structures it into an engaging multi-speaker podcast script, and converts it into realistic audio.

![n8n Canvas Overview](./assets/workflow-canvas.png)

---

## ✨ Key Features
- **Smart Scriptwriting:** Uses Google Gemini to ingest raw text/topics and generate a natural, broadcast-ready conversational script.
- **Automated Audio Generation:** Integrates text-to-speech (TTS) nodes to convert the dialogue into professional audio files.
- **Modular Architecture:** Easily customizable nodes allowing you to swap LLM providers or audio synthesis engines.
- **Plug-and-Play Import:** Clean workflow JSON structure ready to be imported into any standard n8n instance.

---

## 🛠️ Tech Stack & Architecture
* **Automation Engine:** [n8n](https://n8n.io/)
* **Core AI / LLM:** Google Gemini (Chat Model)
* **Audio Synthesis:** Text-to-Speech (TTS) integration nodes
* **Input / Trigger:** Manual trigger, Webhook, or Chat Interface

---

## 📁 Repository Structure
```text
📦 n8n-ai-podcast-generator
 ┣ 📂 assets
 ┃ ┗ 📜 workflow-canvas.png   # Visual screenshot of the n8n workflow canvas
 ┣ 📜 workflow.json           # Exported and sanitized n8n workflow file
 ┗ 📜 README.md               # Project documentation
