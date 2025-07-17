# 🤖 Gemini AI Chatbot API

A simple web-based chatbot using [Google Gemini 1.5 Flash](https://ai.google.dev/) via API, built with Node.js and Express. This project serves a minimal HTML/CSS/JS frontend for chatting with Google's generative AI.

## 🚀 Features

- Built with Express and modern ES modules
- Integration with Google Generative AI (`@google/generative-ai`)
- Clean UI interface for sending and displaying messages
- CORS-enabled and ready for frontend integration

## 📂 Project Structure

```
gemini-chatbot-api/
├── public/
│   ├── index.html        # Frontend UI
│   ├── script.js         # Chat logic & API calls
│   └── style.css         # Basic styling
├── index.js              # Express server and Gemini API integration
├── .env                  # API key (keep secret!)
├── package.json          # Project metadata and dependencies
└── README.md             # You're here!
```

## 🔧 Installation

1. **Clone the repository**

```bash
cd gemini-chatbot-api
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up `.env`**

Create a `.env` file in the root and add your Gemini API key:

```env
GEMINI_API_KEY=your_google_api_key_here
```

4. **Start the server**

```bash
node index.js
```

Then open your browser and go to:

```
http://localhost:3000
```

## 📦 Dependencies

- [Express](https://expressjs.com/)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [cors](https://www.npmjs.com/package/cors)
- [@google/generative-ai](https://www.npmjs.com/package/@google/generative-ai)

## 🛡️ Environment Notes

Make sure your `package.json` includes:

```json
"type": "module"
```

...to support `import` syntax in `index.js`.

## 💡 Future Ideas

- Add streaming responses (like chatGPT style typing)
- Save chat history
- Deploy to Vercel / Render / Railway
- Add markdown or image support

## 🙌 Acknowledgements

- [Google Gemini API Docs](https://ai.google.dev/)
- [MDN Web Docs](https://developer.mozilla.org/)
- Coffee ☕ and Curiosity

---

> **Btw aku masih belajar, open mind banget buat yang mau ngasih masukan atau info lebih lanjut — kita sama-sama belajar ya! 🙌**
