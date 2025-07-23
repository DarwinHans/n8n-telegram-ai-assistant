# 🤖 Telegram AI Assistant con Google Calendar y OpenAI | n8n Workflow

<img width="1199" height="466" alt="Captura de Pantalla 2025-07-23 a la(s) 09 04 36" src="https://github.com/user-attachments/assets/7a72ed7b-9764-4e46-be12-87f7fedd3754" />


Este proyecto es un flujo avanzado de automatización desarrollado en **n8n**, que convierte un bot de Telegram en un asistente virtual inteligente capaz de:

- 📩 Recibir mensajes de texto o audio vía Telegram
- 🧠 Procesarlos con un Agente IA basado en **OpenAI** (GPT-3.5 o GPT-4o)
- 🗓️ Crear, modificar, eliminar y verificar eventos en **Google Calendar**
- 🧼 Limpiar y optimizar las respuestas antes de enviarlas
- 📤 Responder automáticamente en Telegram con texto (y próximamente audio)

---

## ⚙️ Tecnologías y servicios utilizados

- [n8n](https://n8n.io/) como motor de automatización
- [Telegram Bot API](https://core.telegram.org/bots/api)
- [OpenAI API](https://platform.openai.com/)
- [Google Calendar API](https://developers.google.com/calendar)
- [LangChain Toolkit en n8n](https://docs.n8n.io/integrations/langchain/)
- ElevenLabs (opcional para audio de respuesta)

---

## 📌 Características del flujo

- Detección automática del tipo de mensaje: texto o audio.
- Transcripción automática de notas de voz con OpenAI Whisper.
- Agente IA con **memoria contextual** gracias a `Memory Buffer Window`.
- Integración directa con Google Calendar vía herramientas IA.
- Limpieza de texto HTML/símbolos para mejor presentación.
- Respuesta al usuario vía Telegram de forma automática.

---

### 1. Clona este repositorio

```bash
git clone https://github.com/TU_USUARIO/n8n-telegram-ai-assistant.git
cd n8n-telegram-ai-assistant
