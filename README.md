# 📚 StudyBuddy

An AI study assistant that turns your own notes into a personal tutor. Upload PDFs, text files, or pasted notes, then ask questions and get answers with page-number citations.

## 🎥 Demo
[Watch the demo video](WhatsApp%20Video%202026-10-25%20at%2011.18.54%20PM.mp4)

## 🔗 Live page
https://iabhaypal.github.io/StuddyBuddy/

> The AI features need an Anthropic API key. Tap the 🔑 button on the page and paste your key. It is saved only in your own browser. The demo video shows the full working app.

## ✨ Features
- Chat with an AI that remembers the conversation
- "Use my notes" mode: answers cite the source file and page
- Upload PDF, TXT, or Markdown files, or paste text
- Quiz generator: multiple-choice questions from any topic in your notes
- 5 color themes, light and dark mode, drag-and-drop upload

## 🛠️ How it works
1. Notes are split into overlapping chunks that keep their page number.
2. The question is matched to the best chunks using BM25 keyword ranking.
3. The top chunks are sent to Claude, which answers only from them and cites [1], [2].

## 💻 Tech stack
HTML, CSS, JavaScript, PDF.js, Anthropic Claude API

## 🚀 Run it locally
1. Download `index.html`.
2. Open it in any browser.
3. Click 🔑 and add your Anthropic API key.

## 👤 Author
Abhay Pal, B.Tech CSE, Punjab University
