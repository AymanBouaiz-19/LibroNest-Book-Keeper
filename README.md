# 📚 LibroNest – Book Keeper App

A lightweight, smart, and modular application for managing a digital book collection.  
LibroNest allows users to **add**, **remove**, **view**, and **organize** their books using object-based logic and conditional rendering — built as an educational project by a full-stack & AI enthusiast.

---

## 💡 Project Purpose

- Practice object-oriented design
- Strengthen data structure handling (arrays, objects)
- Improve dynamic UI manipulation
- Learn the basics of state, interaction, and DOM events (if extended to JS frontend)
- Prepare for bigger database-driven or cloud-based book apps

---

## 🧰 Core Features

| Feature               | Description                                                      |
|------------------------|------------------------------------------------------------------|
| 📘 Add Book            | Add new books (title, author, genre, year, ISBN, etc.)           |
| 🗑️ Remove Book         | Delete specific books from collection by ID or title             |
| 🔍 Conditional Display | Show books filtered by author, genre, year, or availability      |
| 🧱 Data Structure       | Store book data using arrays of objects                          |
| 💾 Local Storage *(opt)*| Save book list in local storage (if implemented in JS/HTML)     |
| 🖥️ CLI or UI Version    | Can be console-based (Python, C++) or GUI version (HTML/JS)     |

---

## 🧱 Project Structure

LibroNest/ ├── data/                 # Initial book data (JSON, CSV, etc.) ├── src/ │   ├── main.py           # Main script (menu or interaction loop) │   ├── book.py           # Book class (object model) │   ├── manager.py        # Logic for adding/removing/searching │   └── utils.py          # (Optional) for input/output formatting ├── assets/               # UI mockups / screenshots (if any) ├── README.md └── requirements.txt      # If Python or JS version has dependencies

---

## 🧪 Example Usage (CLI)

```Welcome to LibroNest 📚

[1] Add New Book [2] View All Books [3] Search by Genre [4] Delete Book by Title [5] Exit

> You selected: 2


┌────┬────────────────────────────┬────────────────────┬──────┐
│ ID │ Title                      │ Author             │ Year │
├────┼────────────────────────────┼────────────────────┼──────┤
│ 01 │ Atomic Habits              │ James Clear        │ 2018 │
│ 02 │ The Hobbit                 │ J.R.R. Tolkien     │ 1937 │
└────┴────────────────────────────┴────────────────────┴──────┘
```

---

## 🛠️ Technologies Used

- ✅ Python / JavaScript (modular code)
- ✅ JSON / CSV for data storage
- ✅ Optional GUI (HTML/CSS/JS or Tkinter for Python)
- ✅ Object-Oriented Programming
- ✅ (Optional) Local Storage API for JS version

---

## 🌱 Ideas for Extension

| Idea                          | Description                                           |
|-------------------------------|-------------------------------------------------------|
| 🌐 Web Interface              | Convert to web app with HTML/CSS/JavaScript          |
| 🧠 AI Book Recommender        | Suggest similar books using genre/author              |
| 💬 Notes and Reviews          | Add custom notes or reviews per book                  |
| 🔐 User Accounts              | Multi-user version (future feature)                   |
| ☁️ Cloud Sync                | Firebase or MongoDB sync (advanced)                  |

---

## 👨‍💻 Author

**Ayman Bouaziz**  
🎓 *AI & Software Engineering Student – Faculty of Science and Technology Al Hoceima*  
📍 Morocco | 🧠 Python • Web • OOP • AI  

🔗 [LinkedIn](https://www.linkedin.com/in/ayman-bouaziz-7ab181349)  
✉️ projects.aymanbouaziz@gmail.com

---

## 📜 License

MIT — Open for educational and personal use  
© 2025 Ayman Bouaziz

---

## 📘 Final Note

> "LibroNest is more than a digital shelf — it's your personal librarian, coded with care."