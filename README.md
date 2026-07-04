# 🔐 Password Cracking Simulation Tool

> **BCA Final Year Project** — CU Online (Chandigarh University)  
> **Student:** Hardik Sharma  
> **Program:** Bachelor of Computer Application (BCA)  
> **Academic Year:** 2025–2026

---

## 🌐 Live Demo

**👉 [Click here to open the tool](https://YOUR_USERNAME.github.io/password-cracker/)**

> ⚠️ Replace `YOUR_USERNAME` with your actual GitHub username after deploying.

---

## 📌 About the Project

This is a **web-based Password Cracking Simulation Tool** built for educational purposes as part of a BCA final year project. It demonstrates how attackers attempt to recover plaintext passwords from hashed values using two classic techniques — **Dictionary Attack** and **Brute Force Attack** — while also educating users on password security best practices.

The tool runs entirely in the browser. No server, no backend, no installation required.

---

## ✨ Features

| Feature | Description |
|---|---|
| ⚔️ **Dictionary Attack** | Tests passwords from a customizable wordlist against a target hash |
| 💥 **Brute Force Attack** | Systematically tries all character combinations up to a given length |
| **# Hash Generator** | Generates MD5 / SHA-1 / SHA-256 / SHA-512 hashes from plaintext |
| 🛡️ **Password Strength Analyzer** | Rates password strength across 6 security criteria |
| 📋 **Wordlist Generator** | Creates mutation variants from a base keyword |
| 🖥️ **Live Terminal Log** | Real-time color-coded attack log with progress bar |
| ⏹️ **Stop Attack** | Abort any running attack instantly |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling & animations |
| JavaScript (ES6+) | Core logic & algorithms |
| React 18 (CDN) | UI components & state management |
| Babel (CDN) | JSX transpilation in-browser |
| Web Crypto API | SHA-1 / SHA-256 / SHA-512 hashing |
| Pure JS MD5 | MD5 hashing (no external library) |

---

## 🔍 How It Works

### Dictionary Attack
1. User provides a **target hash** and selects the **hash algorithm**
2. Tool loads a **wordlist** (default or custom)
3. Each word is hashed using the selected algorithm
4. If the hash matches the target → **password found!**

### Brute Force Attack
1. User defines a **character set** and **maximum password length**
2. Tool generates every possible combination systematically
3. Each candidate is hashed and compared to the target
4. Exhaustive search until match found or all combinations tried

### Password Strength Analyzer
Checks 6 criteria:
- Minimum 8 characters
- Minimum 12 characters
- Contains lowercase letters
- Contains uppercase letters
- Contains numbers
- Contains special characters

---

## 🚀 How to Use

### Option 1 — Live Website (Recommended)
Just open the link: **`https://YOUR_USERNAME.github.io/password-cracker/`**

### Option 2 — Run Locally
1. Download `index.html`
2. Open it in any modern browser (Chrome, Firefox, Edge)
3. No installation needed!

---

## 📖 Quick Demo Walkthrough

1. Go to the **# Hash** tab
2. Type `password123` → select `SHA-256` → click **GENERATE HASH**
3. Copy the generated hash
4. Go to the **⚔ Crack** tab
5. Paste the hash → select `SHA-256` → choose **Dictionary Attack**
6. Click **▶ START ATTACK**
7. Watch it crack in real-time!

---

## 📂 Project Structure

```
password-cracker/
│
├── index.html          # Complete application (single file)
└── README.md           # This file
```

---

## ⚠️ Disclaimer

> This tool is built **strictly for educational purposes** as part of an academic project.  
> It simulates password cracking techniques to demonstrate cybersecurity concepts.  
> **Do NOT use this tool on any system, account, or hash you do not own or have explicit permission to test.**  
> The author is not responsible for any misuse of this tool.

---

## 📚 Concepts Covered

- Cryptographic hash functions (MD5, SHA family)
- One-way hashing and why passwords are stored as hashes
- Dictionary attacks and the importance of unique passwords
- Brute force complexity and why longer passwords are safer
- Password entropy and strength metrics
- Cybersecurity awareness and best practices

---

## 👨‍💻 Author

**Hardik Sharma**  
Bachelor of Computer Application (BCA)  
CU Online — Chandigarh University  

---

## 📄 License

This project is submitted as an academic assignment under CU Online.  
For educational use only.

---

<div align="center">
  <sub>Made with ❤️ for CU Online BCA Final Year Project</sub>
</div>
