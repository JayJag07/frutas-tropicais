# frutas-tropicais
Full CRUD app with real-time search, localStorage persistence, and add/edit/delete functionality. Built with HTML, CSS, and JavaScript.


A fully functional CRUD (Create, Read, Update, Delete) web application for managing a database of tropical fruits — built with pure HTML, CSS, and JavaScript using the browser's localStorage API.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 🌐 Live Demo

> Upload to GitHub Pages and paste the link here

---

## ✨ Features

- **Create** — add new fruits with name, colour, flavour, and origin
- **Read** — all records displayed in a dynamic, styled table
- **Update** — click any row to populate the form and edit the record
- **Delete** — remove individual records with a single click
- **Real-time search** — filters across all fields instantly as you type
- **Persistent storage** — all data saved to localStorage, survives page refresh
- **Empty state handling** — friendly message shown when no records exist
- **Bug-free search** — corrected filter function for reliable search results

---

## 🛠️ Built With

- HTML5 — semantic form and table structure
- CSS3 — responsive layout, hover effects, button transitions
- JavaScript (ES6+) — localStorage API, array methods (filter, find, push), DOM manipulation

---

## 🐛 Bug Fixed

The original `pesquisarFrutas()` function called `todasFrutas()` as a function instead of using `.filter()` on the array. This has been corrected so search works reliably across all fields.

---

## 📂 Project Structure

```
frutas-tropicais/
├── index.html
├── script.js
└── css/
    └── style.css
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/JayJag07/frutas-tropicais.git
```
2. Open `index.html` in your browser — no build tools or dependencies needed.

---

## 👨‍💻 Author

**Jetro Tchiwana** — [github.com/JayJag07](https://github.com/JayJag07) · [linkedin.com/in/jetrotchiwana](https://linkedin.com/in/jetrotchiwana)
