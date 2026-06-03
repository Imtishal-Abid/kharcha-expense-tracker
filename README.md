# 💰 Kharcha — Personal Expense Tracker

A clean, responsive expense tracking web app built with pure HTML, CSS, and JavaScript. No frameworks, no backend, no database — just a polished single-file web app that runs anywhere.

![Kharcha Expense Tracker](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white)

---

## 🚀 Live Demo

👉 **[View Live App](https://kharcha-expense-tracker-jet.vercel.app/)** 

---

## ✨ Features

- **6 Expense Categories** — Food, Transport, Shopping, Health, Education, Other
- **Summary Dashboard** — Total spent, monthly spending, average per expense, transaction count
- **Donut Chart** — Visual breakdown of spending by category with percentages (Chart.js)
- **Top Categories Bar Chart** — Horizontal bar chart showing highest spending areas
- **Filter by Category** — Quickly view expenses per category
- **Delete & Clear All** — Remove individual or all expenses
- **Persistent Storage** — Data saved in `localStorage`, survives page refresh and browser close
- **Fully Responsive** — Works on mobile, tablet, and desktop
- **Pakistan Locale** — ₨ Rupee currency, local date formatting
- **Smooth Animations** — Slide-in transitions, hover effects, toast notifications

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | App structure |
| CSS3 | Styling, animations, responsive layout |
| Vanilla JavaScript | Logic, DOM manipulation, data handling |
| Chart.js | Donut chart and data visualization |
| localStorage API | Client-side data persistence (no backend needed) |
| Google Fonts (Syne + Inter) | Typography |
| Tabler Icons | UI icons |

---

## 📁 Project Structure

```
kharcha-expense-tracker/
│
└── index.html      ← entire app in one file
```

No build tools. No npm install. No dependencies to manage.

---

## ⚡ Getting Started

### Option 1 — Open directly
```bash
# Just double-click index.html in your file explorer
# Opens in any browser instantly
```

### Option 2 — Live Server (recommended for development)
```bash
# Install live-server globally
npm install -g live-server

# Navigate to the project folder
cd kharcha-expense-tracker

# Start the server
live-server
# Opens at http://127.0.0.1:8080
```

### Option 3 — VS Code Extension
1. Install the **Live Server** extension by Ritwick Dey in VS Code
2. Right-click `index.html` → **Open with Live Server**

---

## 🚀 Deployment

Deployed for free on **Vercel**:
```bash
npm install -g vercel
vercel
```
Or drag and drop the folder into [vercel.com](https://vercel.com) — no configuration needed.

---

## 📸 Screenshots

> *(Add screenshots of your app here after deployment)*
> Tip: Press `F12` → Toggle device toolbar to capture mobile view too.

---

## 🎯 What I Learned

- DOM manipulation and event handling in vanilla JavaScript
- Working with the `localStorage` API for client-side data persistence
- Integrating and configuring Chart.js for data visualization
- Building fully responsive layouts with CSS Grid and Flexbox
- Designing clean, accessible UI with a consistent design system
- Deploying a static web app to Vercel

---

## 👨‍💻 Author

**Imtishal Abid**

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
