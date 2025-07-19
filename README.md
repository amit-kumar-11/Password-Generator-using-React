# Password-Generator-using-React

# 🔐 Simple React Password Generator

This is a minimal React app that generates a **random password** each time the page is refreshed. It's designed for simplicity—no buttons, no user input—just load the page and get a new password instantly.

## 🚀 Features

- Random password generated on every page refresh
- Customizable password length and character set
- Uses basic React hooks (`useState`, `useEffect`)
- Clean and minimal UI


## 🛠️ Tech Stack

- React (Vite)
- JavaScript
- CSS

---

## 🧠 How It Work

On component mount (`useEffect` with empty dependency), the app generates a password using characters from:

- Uppercase A-Z
- Lowercase a-z
- Digits 0-9
- Special characters `!@#$%^&*()_+-=[]{}`
