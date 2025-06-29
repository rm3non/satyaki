# Satyaki

**Satyaki** is a global, developer-first, open-source AI chatbot platform. It is designed to be a cost-effective, self-hostable, plugin-friendly alternative to closed AI systems like OpenAI or DeepSeek.

## 🌟 Features
- 🔌 Plugin-ready architecture (search, documents, APIs)
- 🤖 LLM-agnostic backend (OpenAI or open models like Mistral)
- 🌍 Developer-focused design
- 💸 Self-hostable with free deployment options

## 🚀 Getting Started

### Backend Setup
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend
Open `frontend/index.html` in your browser. Update `script.js` with your backend URL if deploying.

### .env Setup
Copy `.env.example` to `.env` and add your SerpAPI key.

## 🔧 Deployment
You can deploy the backend using [Render](https://render.com) and the frontend using [Vercel](https://vercel.com).

## 🤝 Contributing
We welcome developers to extend Satyaki with plugins. Check `CONTRIBUTING.md` for guidelines.

## 📄 License
MIT