# 📚 React Book App (Hands-on Learning)

This is a beginner-friendly React project where I learned and practiced basic concepts like components and JSX step-by-step.

---

## 🚀 What I Learned

* Creating a React app
* Understanding components
* Writing JSX
* Reusing components

---

## 🛠️ Tech Stack

* React.js
* JavaScript

---

## 📁 Project Structure

```
src/
 ├── App.js
 ├── Book.js
```

---

## ▶️ How to Run

```bash
npm install
npm start
```

---

# 🧠 Hands-on Steps I Followed

---

## 🔹 Step 1: Created React App

```bash
npx create-react-app book-frontend
cd book-frontend
npm start
```

---

## 🔹 Step 2: Edited App.js

Replaced default code with:

```js
import Book from './Book';

function App() {
  return (
    <div>
      <h1>📚 My Favorite Book</h1>

      <Book />
      <Book />
    </div>
  );
}

export default App;
```

---

## 🔹 Step 3: Created Book Component

Created a new file `Book.js`:

```js
function Book() {
  return (
    <div>
      <h3>My Favorite Book</h3>
      <p>Author: senthil</p>
    </div>
  );
}

export default Book;
```

---

## 🔹 Step 4: Used Component Multiple Times

```js
<Book />
<Book />
```

👉 Learned component reuse

---

## 📌 Output

Displays:

* My Favorite Book
* Author: senthil

(repeated multiple times)

---

## 🎯 Key Concepts

* Component = reusable UI block
* JSX = HTML inside JavaScript
* React = builds UI

---

## 🚀 Next Steps (Planned)

* Props (dynamic data)
* Event handling
* API integration

---

## 📞 Need Help?
If you have any questions, feel free to reach out or open an issue. 😊

---

## 👨‍💻 Developed By
This project is developed by Senthil Murugan A K. Feel free to connect with me!
