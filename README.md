### Day 2 — AI Assistant with Conversation Memory

Built a Python-based AI assistant using Ollama and the OpenAI-compatible API. 
The application accepts continuous user input and maintains conversation history during the active session by storing both user messages and AI responses in a `messages` list.
The complete conversation history is sent to the local LLM with each request, allowing the AI to use previous messages as context when responding.
