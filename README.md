# 🛠️ Technical Resume —　kurotya-969

## 👨‍💻 Core Skills

### 💬 Natural Language Interfaces
- Built conversational agents using open-access LLMs (e.g., Together.ai, Groq API, Gemini Pro)
- Designed and refined system prompts for character-driven dialogues
- Implemented memory-like state handling via JSON files (emotion scores, scene context)

### 🧵 Asynchronous Processing
- Developed 2-stage prompt pipelines for deferred content generation (nightly letter-writing)
- Used `asyncio` to manage parallel generation tasks and batch I/O with rate limit handling

### 🖼️ Frontend for AI UX
- Proficient with **Streamlit** for rapid prototyping and deploying chat-style UIs
- Integrated character-based interaction elements (e.g., "backstage mode" toggle, affection meters)
- Deployed apps publicly on Hugging Face Spaces with resource-aware optimizations

### 📡 API Integration
- Experience with RESTful LLM APIs including:
  - **Groq** (scene parsing, ultra-fast inference)
  - **Together.ai** (Qwen 1.5 72B/235B, for high-quality text generation)
- Designed fallback and routing logic across providers for stability and cost-efficiency

### 🧠 Prompt Engineering
- Built complex, multi-layered prompts to control:
  - Character behavior and tone
  - Emotional variability (e.g., tsundere-like hesitation)
  - Structured output formats (e.g., JSON scene labels, Markdown letters)
- Developed meta-prompts that dynamically reflect system state or user history

### 🗃️ Data Handling & Persistence
- Stateless architecture using JSON-based "soft memory"
- Emotion scores, affection levels, and topic history stored without database
- Plan for migration to SQLite for scalability

---

## 🚀 Notable Project

### 📌 Mari Chat — Emotionally-Aware AI Character App  
**[View project](https://huggingface.co/spaces/sirochild/mari)**

A bilingual (JP/EN) AI chatbot featuring:

- 🧠 Groq-powered scene analysis & character switching
- 💌 Asynchronous letter generation (overnight batch with 2-pass prompts)
- 🧬 Emotion and memory management without a traditional backend
- 🎭 Toggleable "Backstage Mode" to reveal hidden internal thoughts

Technologies: `Streamlit`, `Python`, `Groq`, `Together.ai`, `asyncio`, `JSON`, `Hugging Face Spaces`

---

## 🏆 Recognition & Publications

- 🎖️ Entry accepted — **U-22 Programming Contest 2025**
- ✍️ [Zenn article](https://zenn.dev/sirochild/articles/87d46e44ab27a7) on building a full-stack AI app with no budget
- 👥 Featured in discussions on minimal-resource AI architecture

---

## 📍 Contact & Links

- GitHub: [@sirochild](https://github.com/sirochild)
- Zenn: [@sirochild](https://zenn.dev/sirochild)

