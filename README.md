# Diet Breakdown Calculator

A responsive, dark-themed single-page web application for calculating daily caloric intake and macronutrient targets (protein, fats, carbohydrates, fiber, and water) based on body weight.

---

## 🥗 Overview

**Diet Breakdown Calculator** helps users quickly determine their nutritional targets tailored to their body weight. It features an interactive, clean dark-mode interface, instant real-time calculations, and persistent local storage so your saved weight is automatically restored whenever you return.

---

## 📊 Nutritional Formulas

The calculator applies the following macronutrient and hydration formulas based on body weight (`W` in kilograms):

| Metric | Formula | Description |
| :--- | :--- | :--- |
| **Calories** | `W × 26 kcal` | Daily baseline caloric intake |
| **Protein** | `W × 2.0 g` | Optimal daily protein target for muscle preservation and recovery |
| **Fats** | `W × 0.866 g` | Healthy fat intake for hormone production and general health |
| **Fiber** | `38 g` | Recommended daily dietary fiber baseline |
| **Carbs** | `268 g` | Baseline carbohydrate intake |
| **Water** | `3.5 L` | Daily hydration target |

---

## ✨ Features

- **Instant Calculations:** Results update in real-time as you type your body weight.
- **LocalStorage Persistence:** Remembers your weight across browser sessions.
- **Clean Dark Theme:** High-contrast, eye-friendly dark design with gold/yellow accent colors.
- **Zero Dependencies:** Pure HTML5, CSS3, and vanilla JavaScript — no frameworks or build steps required.
- **Mobile Friendly:** Fully responsive card layout optimized for phones, tablets, and desktops.

---

## 🚀 Getting Started

### Option 1: Direct File
Simply open [`index.html`](index.html) in any modern web browser (Chrome, Firefox, Safari, Edge).

### Option 2: Local Server
You can also serve it with any lightweight HTTP server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```
Then navigate to `http://localhost:8000` in your browser.