
# 🔐 React Password Generator

A clean, responsive, and interactive password generator built with **React** and **Tailwind CSS**. This app lets users generate secure passwords with customizable options like length, numbers, and special characters — and includes a copy-to-clipboard feature.

---

## ✨ Features

- 🔢 Adjustable password length (6 to 100 characters)
- 🔁 Toggle to include:
  - Numbers (`0-9`)
  - Special characters (`!@#$%^&*`, etc.)
- ⚡ Auto-generate passwords on input change
- 📋 One-click copy to clipboard
- 🎨 Fully responsive with modern UI using Tailwind CSS

---

## 🧠 Tech Stack

- **React** – Functional components and React hooks
- **Tailwind CSS** – Utility-first styling for a responsive layout
- **Clipboard API** – Native JavaScript API for copying to clipboard

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/password-generator.git
cd password-generator
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

> ⚠️ Ensure Node.js and npm are installed on your machine.

---

## 📁 Project Structure

```
password-generator/
├── public/
├── src/
│   ├── App.jsx        # Main application logic
│   ├── App.css        # Optional custom styles
│   └── main.jsx       # React entry point
├── index.html
├── tailwind.config.js
└── package.json
```

---

## 🧩 Concepts Demonstrated

- **`useState`**: Manage UI and password state
- **`useEffect`**: Auto-generate new password on changes
- **`useCallback`**: Memoize generation logic for optimization
- **`useRef`**: Access DOM for clipboard copying
- **Clipboard API**: Copy password with one click

---

## 📸 Screenshot

> *(Include this image in your repo as `screenshot.png`)*

![Password Generator Screenshot](./screenshot.png)

---

## 🌐 Live Demo

> Add your hosted URL here if deployed  
[🔗 Live Demo](https://your-deployment-url.vercel.app)

---

## 📜 License

This project is open source under the [MIT License](LICENSE).

---

## 🙌 Contribution

Feel free to open an issue or submit a pull request!

---

### 💡 Author

Made with ❤️ by [vinay adari](https://github.com/vinayadari)
