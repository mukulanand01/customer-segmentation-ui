# Customer Segmentation UI

A modern and responsive customer segmentation landing page built using **React**, **Vite**, and **Tailwind CSS**. The project showcases a clean fintech-inspired interface with interactive customer cards and a responsive layout.

---

## 🚀 Live Demo

Add your deployed link here:

https://your-live-demo-link.com

---

## 📸 Preview

Add your project screenshot here.

Example:

![Project Screenshot](./src/assets/images/screenshot.png)

---

## ✨ Features

- Modern and clean UI
- Responsive design
- Customer segmentation cards
- Reusable React components
- Built with Tailwind CSS
- Fast development using Vite
- Component-based architecture

---

## 🛠️ Tech Stack

- React
- Vite
- Tailwind CSS
- JavaScript (ES6)
- HTML5
- CSS3

---

## 📂 Folder Structure

```
customer-segmentation-ui
│
├── public
│
├── src
│   ├── assets
│   │
│   ├── components
│   │   ├── Section1
│   │   │   ├── Arrow.jsx
│   │   │   ├── HeroText.jsx
│   │   │   ├── LeftContent.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── Page1Content.jsx
│   │   │   ├── RightCard.jsx
│   │   │   ├── RightCardContent.jsx
│   │   │   ├── RightContent.jsx
│   │   │   └── Section1.jsx
│   │   │
│   │   └── Section2
│   │       └── Section2.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
└── README.md
```

---

# 🔄 Component Flow

```
main.jsx
      │
      ▼
   App.jsx
      │
      ├───────────────┐
      ▼               ▼
 Section1         Section2
      │
      ▼
Page1Content
      │
 ┌────┴───────────────┐
 ▼                    ▼
LeftContent      RightContent
 │                    │
 │                    ▼
 │               RightCard
 │                    │
 │                    ▼
 │             RightCardContent
 │
 ├── Navbar
 ├── HeroText
 └── Arrow
```

---

## 📖 How It Works

### App.jsx

- Stores all customer card data.
- Passes the data to `Section1` using props.
- Renders `Section2`.

---

### Section1

Acts as the main landing page.

Contains

- Navbar
- Left Content
- Right Content

---

### Navbar

Displays

- Target Audience
- Digital Banking Platform

---

### Left Content

Displays

- Heading
- Description
- Arrow Icon

---

### Right Content

Loops through the users array and renders all customer cards.

---

### RightCard

Displays

- Customer Image
- Number
- Description
- Category Button

---

### RightCardContent

Contains

- Card Text
- Tag Button

---

### HeroText

Displays the large heading.

---

### Arrow

Displays the bottom arrow icon.

---

### Section2

Second section of the landing page.

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/mukulanand01/customer-segmentation-ui.git
```

Go inside the project

```bash
cd customer-segmentation-ui
```

Install dependencies

```bash
npm install
```

Run the project

```bash
npm run dev
```

---

## 👨‍💻 Author

**Mukul Anand**

GitHub:
https://github.com/mukulanand01

LinkedIn:
(Add your LinkedIn profile here)

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub.






