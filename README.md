# 🤖 Greeting Bot

A simple and interactive **JavaScript Greeting Bot** that displays a personalised message based on user input.  
Built to practise **DOM manipulation**, **event handling**, and basic **UI updates**.

## ✨ Features
- Takes the user's name and generates a custom greeting  
- Clean and minimal UI  
- Fully responsive and centered layout  
- Beginner‑friendly JavaScript logic  

## 🛠️ Technologies Used
- **HTML**  
- **CSS**  
- **JavaScript**

## 📚 What I Learned
- How to handle **click events** in JavaScript  
- How to update the **DOM dynamically**  
- How to link and structure **HTML, CSS, and JS** files  
- How to deploy a simple project using **GitHub Pages**

## ⏳ Future Improvements
- Add multiple greeting styles  
- Add time‑based greetings (morning/afternoon/evening)  
- Add animations or sound effects  

## 📁 Project Structure
```
index.html  
style.css  
script.js  
```

## 💡 How to Use
1. Type your name in the input field  
2. Click **Greet me**  
3. Enjoy your personalised message! 🎉

## 📝 About This Project

This project was originally created as a **FreeCodeCamp JavaScript exercise**, where the goal was to practise working with variables and `console.log()` output.  
The original script was **not designed to interact with the page**, and it only displayed messages inside the browser console.

To make the project more fun and presentable on **GitHub Pages**, I added a small extra JavaScript snippet that connects the HTML button and input field to the page.  
This addition does **not modify the original FCC exercise**, but simply makes the demo more interactive and user‑friendly.

Here is the small enhancement added at the end of the file:

```javascript
document.getElementById("btn").addEventListener("click", function () {
  const name = document.getElementById("nameInput").value;
  document.getElementById("message").textContent = "Hello " + name + "!";
});
```

This allows the page to display a personalised greeting while keeping the original FCC code fully intact.
   
