# 💰 Capital One Savings Dashboard

A responsive, interactive web application that empowers users to track their income, spending, and savings while receiving personalized financial insights. Built with HTML, CSS, and JavaScript, this project simulates a user dashboard experience for a fictional Capital One savings platform.

---

## 📁 Project Structure

| File/Folder              | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `index.html`             | Landing page with sections for Hero, About, and Mission                    |
| `dashboard.html`         | Main user dashboard with widgets, forms, and chatbot                        |
| `login.html`             | Login page for existing users                                               |
| `signup.html`            | Signup page for new users                                                   |
| `scripts.js`             | JavaScript logic for fetching and displaying user financial data            |
| `sheets/`                | Folder containing CSS stylesheets                                           |
| `images/`                | Folder containing logos, icons, and illustrations                           |

---

## 🚀 Features

### 🧭 Landing Page (`index.html`)
- Smooth scrolling navigation
- Hero section with call-to-action
- About and Mission sections
- Responsive layout with custom fonts and imagery

### 📊 Dashboard (`dashboard.html`)
- Displays:
  - Total Balance
  - Income
  - Spending
  - Save vs Spending
  - Spend-to-Income Ratio (STIR)
- Visual feedback with thumbs up/down based on STIR
- Reward system that increments based on savings behavior
- Deposit and transaction forms
- AI-powered chatbot ("Ask Howard") for financial advice

### 🔐 Authentication Pages
- **Login (`login.html`)**: Secure form for existing users
- **Signup (`signup.html`)**: Registration form for new users

### 🧠 AI Chatbot
- Integrated with OpenAI via CDN
- Users can ask financial questions and receive real-time responses

---

## 🧠 Dynamic Dashboard Logic (`scripts.js`)
- Parses `username` from URL query parameters
- Fetches user-specific data from `/dashboard?username=...`
- Calculates and displays:
  - Total income and spending
  - Balance and savings metrics
  - Spend-to-Income Ratio with visual feedback
  - Reward count based on savings behavior

