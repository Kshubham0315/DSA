# 💡 DSA Instructor – AI-Powered Q&A Web App

A frontend-only web application that uses **Google Gemini (GenAI)** to answer **Data Structures & Algorithms** (DSA) related questions. If the user asks anything off-topic, the AI replies **rudely**, just like a strict DSA instructor! 🤖

---

## 🧠 Features

- 🎓 Ask any DSA-related question (like arrays, stacks, sorting, etc.)
- 🤬 Get sarcastic or rude responses for non-DSA questions
- 🌐 100% frontend — no backend required
- 🧬 Powered by **Google Gemini 1.5 Flash** via REST API
- 💅 Beautiful modern UI with responsive layout

---

## 🛠️ Tech Stack

- **HTML** – Structure  
- **CSS** – Styling (responsive + dark theme)  
- **JavaScript** – API integration & logic  
- **Google GenAI** – Natural language model (via REST)

---

## 🔥 Live Demo

You can open the project by just clicking the `index.html` file in any browser (Chrome, Edge, etc).

> ⚠️ _Note: The API key is publicly used for demo/testing. Please avoid misuse. In production, never expose your API key in frontend code._

---

## 🚀 How to Use

1. Clone or download the repository  
2. Open `index.html` in your browser  
3. Type a question (e.g., `What is a Binary Tree?`)  
4. Click `Get Answer`  
5. Try a non-DSA question like `How are you?` to see the strict side 😅

---

## 📸 Screenshots

| Ask DSA Question        | Ask Off-topic Question         |
|-------------------------|-------------------------------|
| ![DSA Answer](screenshot-dsa.png) | ![Rude Reply](screenshot-rude.png) |

---

## 📌 Example Prompts

✅ _"What is a linked list?"_  
✅ _"Explain quicksort with time complexity."_  
❌ _"What is your name?"_ → _"You dumb, ask me some sensible question."_
