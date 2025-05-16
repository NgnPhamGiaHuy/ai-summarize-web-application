# 🤖 AI Article Summarizer

[![React](https://img.shields.io/badge/React-18.2.0-blue.svg)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-4.4.5-purple.svg)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.3.3-teal.svg)](https://tailwindcss.com/)
[![Redux](https://img.shields.io/badge/Redux-8.1.2-purple.svg)](https://redux.js.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)

## 📝 Description

AI Article Summarizer is a web application that transforms lengthy articles into clear, concise summaries with the power of OpenAI GPT-4. Simply paste any article URL and get an instant AI-generated summary, making content consumption faster and more efficient.

This application leverages the Article Extractor and Summarizer API from RapidAPI, combined with a modern React-based frontend to deliver a seamless user experience. All previously summarized articles are saved locally for quick access.

## ✨ Features

- **Summarize any web article** with a simple URL paste
- **Save summaries locally** for future reference
- **Copy article URLs** with one click
- **Remove saved articles** from history
- **Responsive design** works on desktop and mobile devices
- **Modern UI** with clean, intuitive interface
- **Fast processing** via RapidAPI's Article Summarizer service

## 🖼️ Demo

![AI Article Summarizer Demo](https://github.com/HinhNhuLaHuy/Web-Application-AI-Summarize/assets/84061230/4ffd4042-f929-4f8a-b1e4-198335772378)

## ⚙️ Installation

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn

### Setup

```bash
# Clone the repository
git clone https://github.com/ngnphamgiahuy/ai-summarize-web-application.git

# Navigate to the project directory
cd ai-summarize-web-application

# Install dependencies
npm install

# Create .env file with your RapidAPI credentials
echo "VITE_RAPID_API_ARTICLE_KEY=your_rapidapi_key" > .env
echo "VITE_RAPID_API_ARTICLE_HOST=article-extractor-and-summarizer.p.rapidapi.com" >> .env
```

## 🚀 Usage

```bash
# Start the development server
npm run dev

# Build for production
npm run build

# Preview the production build
npm run preview
```

Once started, open your browser and visit: `http://localhost:5173/`

## 🔧 Configuration

Create a `.env` file in the root directory with the following variables:

```env
VITE_RAPID_API_ARTICLE_KEY=your_rapidapi_key
VITE_RAPID_API_ARTICLE_HOST=article-extractor-and-summarizer.p.rapidapi.com
```

To get your API key:
1. Sign up at [RapidAPI](https://rapidapi.com/)
2. Subscribe to the [Article Extractor and Summarizer API](https://rapidapi.com/restyler/api/article-extractor-and-summarizer)
3. Copy your API key from the dashboard

## 🗂️ Folder Structure

```
├── src/                  # Source files
│   ├── assets/           # Images and icons
│   ├── components/       # React components
│   │   ├── Demo.jsx      # Article summarizer main component
│   │   ├── Hero.jsx      # Header component
│   │   └── index.js      # Components export file
│   ├── services/         # API and state management
│   │   ├── article.js    # Article API integration
│   │   └── store.js      # Redux store configuration
│   ├── App.jsx           # Main application component
│   ├── App.css           # Application styles
│   └── main.jsx          # Entry point
├── public/               # Static files
├── .env.example          # Environment variables template
├── index.html            # HTML entry point
├── package.json          # Project dependencies
├── tailwind.config.js    # Tailwind CSS configuration
├── vite.config.js        # Vite configuration
└── README.md             # This file
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

```bash
# Fork the repository
# Clone your fork
git clone https://github.com/ngnphamgiahuy/ai-summarize-web-application.git

# Create your feature branch
git checkout -b feature/amazing-feature

# Commit your changes
git commit -m "Add some amazing feature"

# Push to the branch
git push origin feature/amazing-feature

# Open a Pull Request
```

## 🙏 Acknowledgements

- [OpenAI](https://openai.com/) for the GPT-4 technology
- [RapidAPI](https://rapidapi.com/) for the Article Extractor and Summarizer API
- [React](https://reactjs.org/) and [Redux Toolkit](https://redux-toolkit.js.org/) for the frontend framework
- [Tailwind CSS](https://tailwindcss.com/) for the styling
- [Vite](https://vitejs.dev/) for the build tool
