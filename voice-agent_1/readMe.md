# Voice Agent 1

A real-time AI Voice Agent built with **n8n**, **ElevenLabs**, and **OpenRouter**.

The workflow accepts voice input from a web interface, converts it into text, processes it with an AI model, converts the response back into speech, and returns the generated audio to the client.

---

## Features

- 🎤 Voice recording from browser
- 🔗 Webhook-based communication
- 📝 Speech-to-Text using ElevenLabs
- 🤖 AI response generation using OpenRouter
- 🔊 Text-to-Speech using ElevenLabs
- 🌐 Simple Glassmorphism HTML interface
- ⚡ Real-time voice conversation

---

## Workflow

```text
Browser
   │
   ▼
HTML UI
   │
   ▼
Webhook
   │
   ▼
ElevenLabs
(Speech → Text)
   │
   ▼
AI Agent
(OpenRouter)
   │
   ▼
ElevenLabs
(Text → Speech)
   │
   ▼
Respond to Webhook
   │
   ▼
Browser plays AI response
```

---

## Project Structure

```
voice-agent_1/
│
├── voice-agent_1.json
├── index.html
└── README.md
```

---

## Technologies Used

- n8n
- ElevenLabs API
- OpenRouter API
- HTML
- CSS
- JavaScript

---

## Workflow Nodes

1. Webhook
2. ElevenLabs Speech-to-Text
3. AI Agent (OpenRouter)
4. ElevenLabs Text-to-Speech
5. Respond to Webhook

---

## 🎯 How It Works

1. User records their voice from the browser.
2. Audio is sent to the n8n webhook.
3. ElevenLabs converts speech into text.
4. OpenRouter generates an AI response.
5. ElevenLabs converts the response into speech.
6. Audio is returned through the webhook.
7. Browser automatically plays the AI response.

---

## Interface

A lightweight Glassmorphism-based web interface is included for interacting with the workflow.

Features:

- Record voice
- Send audio
- Play AI response
- Responsive design

---

## Future Improvements

- Conversation memory
- Streaming responses
- Multiple AI models
- Voice selection
- Chat history
- Authentication
- Better error handling

---

## 👨‍💻 Author

Built while learning automation with **n8n**, AI APIs, and workflow development.