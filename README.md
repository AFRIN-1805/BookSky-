# 📚 Booksky

Booksky is a simple web application to add, view, and delete book entries.  
It uses **HTML**, **CSS**, and **JavaScript** to dynamically manage books on the page without requiring a page reload.

---

## 🚀 Features
- **Add Books**: Enter book title, author, and description through a popup form.
- **Delete Books**: Remove books instantly from the list.
- **Popup Form**: Clean, user-friendly popup for book entry.
- **Responsive Design**: Works well on desktop, tablet, and mobile.
- **Dynamic Content**: Books are added to the DOM without reloading the page.

---

## 🛠️ Technologies Used
- **HTML5** – Structure of the page
- **CSS3** – Styling and responsiveness
- **JavaScript (Vanilla)** – Interactivity and DOM manipulation
- **Google Fonts** – "Playwrite NG Modern" font

---

## 📂 Project Structure
booksky/
│
├── index.html # Main HTML file
├── style1.css # Stylesheet
├── script.js # JavaScript functionality
└── README.md # Project documentation

---

## 📖 How It Works
1. Click the **"+" button** at the bottom right to open the "Add Book" popup.
2. Fill in the **Title**, **Author**, and **Description**.
3. Click **Add**:
   - A new book card is created and appended to the page.
   - Popup closes automatically.
4. Click **Delete** on any book card to remove it.

---

## 💻 Live Demo
*(https://lustrous-parfait-c0697b.netlify.app/)*

---

## 📸 Screenshots
*<img width="1914" height="944" alt="image" src="https://github.com/user-attachments/assets/73bf5607-2afc-4b08-a79a-cf3d65e3d0c1" />
*

---

## 📝 Code Highlights
- **Dynamic Book Creation:**
```javascript
var div = document.createElement("div");
div.setAttribute("class", "book-container");
div.innerHTML = `<h1>${booktitleinput.value}</h1>
<h5>${bookauthorinput.value}</h5>
<p>${bookdescriptioninput.value}</p>
<button onclick="deletebook(event)">Delete</button>`;
container.append(div);
