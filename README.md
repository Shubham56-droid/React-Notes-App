# 📝 Notes App (React)

A simple and clean **React Notes App** that allows you to create, edit, color and delete notes.  
Fully built using **React Hooks** and basic CSS.

---

## ✨ Features (Based on the Code)

### ✅ Add Notes
- Click the **+ button** to open the note box.
- Type your note in the textarea.
- Save using the **check icon**.

### 🎨 Choose Note Colors
- Select from 5 predefined colors.
- New note gets the selected color as background.

### ✏️ Edit Notes
- Click the **edit icon** on a note.
- The textarea becomes editable.
- After editing, click the **check icon** to save.

### 🗑️ Delete Notes
- Remove any note instantly using the **trash icon**.

### 🧩 Smooth UI State Handling
- Uses multiple states like:
  - `isactive` — open/close sidebar
  - `addbox` — show/hide new note box
  - `updateIdx` — to track which note is being edited
  - `data` — stores the notes list

### ⚛️ React Hooks Used
- `useState` for state management
- Controlled inputs (`textarea`)
- Array methods (`map`, `filter`) for CRUD

### Screenshot
<img src="./images/image (15).png"/>
<img src="./images/image (5).png"/>
---

## 📂 Project Structure

```
src/
│── App.jsx
│── App.css
│── index.js
```

---

## 🚀 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/notes-app.git

# Navigate into the project
cd notes-app

# Install dependencies
npm install

# Start the development server
npm start
