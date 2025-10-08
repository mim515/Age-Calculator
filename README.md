# 🧮 Age Calculator

**🔗 Live Demo:** [https://mim515.github.io/Age-Calculator/](https://mim515.github.io/Age-Calculator/)

A simple and interactive web app that lets users enter their birthdate and instantly calculates their age in years.  
Built with **HTML, CSS, and JavaScript**, this project demonstrates the use of basic web technologies, DOM manipulation, and date handling in JavaScript.

---

## 📑 Table of Contents

- [Features](#features)  
- [How It Works](#how-it-works)  
- [Tech Stack](#tech-stack)  
- [Usage / Installation](#usage--installation)  
- [Customization](#customization)  
- [Contributing](#contributing)  
- [License](#license)

---

## ✨ Features

- User-friendly date picker for entering your birthdate  
- Real-time calculation of age based on the current date  
- Automatically adjusts if the birthday hasn’t occurred yet this year  
- Clean, minimal, and responsive design  
- Smooth hover and transition effects for better UI experience  

---

## ⚙️ How It Works

1. The user selects a birthdate from the date input field.  
2. JavaScript retrieves this date and creates a `Date` object.  
3. The current date is also fetched using `new Date()`.  
4. The app subtracts the birth year from the current year to get a preliminary age.  
5. Then it checks if the current month and day are before the birth month and day:  
   - If yes, it subtracts 1 from the calculated age (since the birthday hasn’t happened yet).  
6. The final age is displayed dynamically inside the result box.

---

## 🧠 Tech Stack

- **HTML** – for structure  
- **CSS** – for styling and responsiveness  
- **JavaScript (Vanilla)** – for logic and interactivity  

No frameworks or libraries are used — everything is written in pure code.

---

## 🚀 Usage / Installation

### Option 1: Try the Live Demo
👉 [Click here to open the live version](https://mim515.github.io/Age-Calculator/)

### Option 2: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/mim515/Age-Calculator.git
