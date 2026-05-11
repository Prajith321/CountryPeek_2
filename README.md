# CountryPeek 🌍

CountryPeek is a React-based web application that allows users to search for countries and instantly view important information such as flags, population, region, and capital city using the RestCountries API.

This project was built as part of the Kalvium Front-end assignment using React, Vite, React Router, CSS Grid, and Fetch API.

---

## 🚀 Features

- 🔎 Live country search
- ⚡ Debounced API requests (400ms delay)
- 🌎 Fetches real-time country data from RestCountries API
- 🖼️ Country cards with:
  - Flag
  - Country name
  - Population
  - Region
  - Capital
- 📱 Responsive CSS Grid layout
- ⏳ Loading state handling
- ❌ Error handling for invalid searches
- 🔗 React Router integration for future detail pages
- 🧹 Clean and modular folder structure

---

## 🛠️ Tech Stack

- React
- Vite
- React Router DOM
- CSS3
- JavaScript (ES6+)
- RestCountries API

---

## 📂 Folder Structure

```bash
src/
│
├── components/
│   ├── Header.jsx
│   ├── SearchBar.jsx
│   └── CountryCard.jsx
│
├── pages/
│   ├── Home.jsx
│   └── NotFound.jsx
│
├── styles/
│   └── App.css
│
├── App.jsx
├── main.jsx
└── routes/
