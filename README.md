# Catholic-chatbot
A gpt style chatbot that will answer Catholic questions based on the Catechism &amp; the Bible, that calls OpenAI to complete the requests but with the restriction of only using the Catechism of the Catholic Church and the Bible as references. (Future versions may also reference homilies and other documents from church fathers and doctors of the Church)

# CRUD Implementation
Using a CRUD to make requests and then putting each question asked into DynamoDB and referencing it if the same question is asked to mitigate calls to OpenAI. Future improvements will include adding semantic similarity function to make even less calls to OpenAI.

# 🚀 Catholic Chatbot

> A gpt style chatbot that will answer Catholic questions based on the Catechism &amp; the Bible.

---

## 📖 Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

---

## ✅ Features
- 🔒 Secure authentication
- 📦 Clean architecture
- ⚡ Fast and lightweight

---

## 🎬 Demo
![App Screenshot](docs/screenshot.png)  
Live Demo 👉 [yourproject.com](https://yourproject.com)

---

## 🛠️ Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/project-name.git

# Navigate into project folder
cd project-name

# Install dependencies
npm install

# Run the app
npm run dev
