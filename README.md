# Fast React Pizza Menu 

A small but well-structured React application that renders a pizza menu using reusable components, props and conditional rendering.  
Built to demonstrate strong React fundamentals and clean UI logic.

---

## Overview

This project simulates a simple restaurant menu for a pizzaria or pizza shop.  
It dynamically renders menu items, handles sold-out states and displays different UI based on business hours.

The goal of this project is **not complexity**, but **clarity and correctness** in React fundamentals.

---

## Features

- Component-based architecture
- Dynamic list rendering using `Array.map`
- Conditional rendering for:
  - Empty menu state
  - Sold-out pizzas
  - Business open/closed hours
- Reusable and readable components
- Clean JSX and predictable data flow

---

## Concepts Demonstrated

- **JSX syntax**
- **Props** for passing structured data
- **Conditional rendering** (ternaries and early returns)
- **Dynamic class names**
- **Separation of concerns**
- **Rendering lists with keys**
- **Basic UI business logic**

---

## Component Breakdown

- `App` – Root component and layout
- `Header` – Application title
- `Menu` – Renders menu and handles empty state
- `Pizza` – Individual pizza item component
- `Footer` – Handles business-hour logic
- `Order` – Call-to-action when restaurant is open

---


---

## Business Logic

- Menu renders only when pizza data exists
- Sold-out pizzas are visually styled and labeled
- Footer UI changes depending on current time
- Restaurant is open between **12:00 – 22:00**

---

## Tech Stack

- **React 18**
- **JavaScript (ES6+)**
- **CSS**
- **Create React App / Vite-compatible structure**

---

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/fast-react-pizza-menu.git
   
2. Install dependencies
   ```bash
   npm install

3. Start the development server
   ```bash
   npm start

## Potential Improvements

Extract components into separate files

Move pizza data to an external JSON or API

Introduce useState for ordering flow

Add filtering (e.g., vegetarian, price range)

Improve accessibility (ARIA roles, semantic HTML)

Add basic tests

## Learning Context

I built this project while learning React fundamentals, focusing on:

Thinking in components

Data-driven UI

Predictable rendering logic

