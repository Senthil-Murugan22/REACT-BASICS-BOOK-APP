<<<<<<< HEAD
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


## 👨‍💻 Developed By
This project is developed by [Senthil Murugan A K](https://github.com/Senthil-Murugan22). Feel free to connect with me!
=======
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
>>>>>>> 03574e4 (Initialize project using Create React App)
