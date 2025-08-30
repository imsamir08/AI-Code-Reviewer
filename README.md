🧑‍💻 AI Code Reviewer

🚀 AI Code Reviewer – A web app that uses Gemini AI to analyze your code, detect errors, and suggest improvements in real time.


🔹 Features

✨ AI-Powered Code Review – Detects mistakes, errors, and bad practices.

⚡ Real-Time Suggestions – Provides instant improvement tips with explanations.

📝 Markdown Rendering – Cleanly displays AI feedback with formatting.

🎨 Syntax Highlighting – Enhanced readability with prismjs and rehype-highlight.

🌐 Full-Stack Integration – Built with React (Vite) + Node.js (Express).


🛠️ Tech Stack

Frontend: React, Vite, Axios, React Markdown, PrismJS

Backend: Node.js, Express, CORS

AI Integration: Google Gemini API

Code Quality: ESLint


📂 Project Structure
├── server.js        # Node.js backend entry
├── src/             # React frontend source code
├── package.json     # Dependencies & scripts
├── vite.config.js   # Vite configuration
└── .env             # Gemini API key (ignored in git)


⚙️ Setup & Installation

1. Install dependencies

npm install


2. Add your Gemini API key in .env

GOOGLE_GEMINI_KEY=AIzaSyDGploiULslA-JbkjPO8k67-O3ITnDa_08


3. Run backend (Express server)

node server.js


4. Run frontend (Vite + React)

npm run dev


5. Open in browser

http://localhost:5173/



📌 Future Improvements

✅ Add user authentication (JWT)

✅ Support multiple programming languages

✅ Export AI feedback as PDF/Markdown

📜 License

MIT License – feel free to use and modify.
