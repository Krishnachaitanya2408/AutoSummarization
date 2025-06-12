# 📄 Doc Assistant – AI-Powered PDF Analysis Tool

Doc Assistant is an intelligent web application that transforms complex PDF documents into clear summaries and generates insightful Q&A pairs using Google's Gemini AI. Whether you need a quick overview or detailed analysis, Doc Assistant makes document comprehension effortless.

## 🌟 Features

- 🔍 Three-tier summarization levels (Abstract/Summary/Article)
- 📝 Automated Q&A generation from document content
- 📋 One-click copy functionality
- 💫 Real-time processing feedback
- 🎨 Modern, responsive interface

## 🧠 How It Works

Doc Assistant processes your PDF documents by:

1. Extracting text content
2. Analyzing context using Gemini AI
3. Generating structured summaries and Q&A pairs
4. Presenting results in an easy-to-read format

## 🏗️ Technical Architecture

### 🔹 Frontend

- ⚛️ React + Vite
- 🎨 Tailwind CSS
- 📡 Axios for API calls
- 🛣️ React Router for navigation

### 🔹 Backend

- 🌐 Flask API
- 📑 PyMuPDF for PDF processing
- 🤖 Google Gemini AI for text generation
- 🔒 CORS handling

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/Krishnachaitanya2408/AutoSummarization.git
cd AutoSummarization
```

### 2. Install Dependencies

🔧 Frontend

```bash
npm install
```

🔧 Backend

```bash
pip install -r requirements.txt
```

### 3. Environment Setup

Create a `.env` file in the backend directory:

```
GOOGLE_API_KEY=your_api_key_here
```

### 4. Run Development Servers

Frontend:

```bash
npm run dev
```

Backend:

```bash
python backend/logic.py
```

## 📦 Core Dependencies

### Frontend

- React
- Tailwind CSS
- Vite
- Axios
- React Router

### Backend

- Flask
- PyMuPDF
- Google Generative AI
- python-dotenv
- flask-cors

## 🤝 Contributing

We welcome contributions! To contribute:

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

## 👥 Authors

- Your Name
- Contributors

## 🙏 Acknowledgments

- Google Generative AI team for Gemini
- PyMuPDF developers
- React and Vite communities
- Open-source contributors


