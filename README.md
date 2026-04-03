# 🕌 Prayer Times & Quran Web App

A production-ready **front-end web application** that integrates real-time APIs to deliver accurate daily prayer schedules and Quran content through a clean, responsive, and scalable interface.

The project demonstrates strong front-end engineering fundamentals including API integration, state management, and multi-page architecture — all built using **Vanilla JavaScript** without frameworks.

---

## 🚀 Key Features

### 🕰️ Prayer Times

* Fetches real-time prayer times based on user location
* Displays a structured daily schedule
* Handles API response parsing and dynamic rendering

### 📖 Quran Integration

* Browse Quran content via external API
* Dynamic loading of surahs and ayahs
* Clean and readable interface optimized for content consumption

### 🎨 User Experience

* Multi-page navigation architecture
* Responsive design across all screen sizes
* Smooth UI updates with minimal reloads

### 💾 Data Handling

* Lightweight state persistence using `localStorage`
* Efficient asynchronous API handling

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **UI Framework:** Bootstrap
* **APIs:** Prayer Times API, Quran API
* **Concepts:** REST API integration, Async JavaScript, Local Storage

---

## 📂 Project Structure

```bash
/assets        → Static resources (images, icons)
/css           → Styles and layout
/js            → Core logic (API calls, DOM manipulation)
/pages         → Application pages (Prayer, Quran, etc.)
index.html     → Entry point
```

---

## 🏗️ Architecture

The application follows a **multi-page client-side architecture**, where each page is powered by dedicated JavaScript logic.

* Clear separation between UI and logic layers
* Modular JavaScript structure for maintainability
* Dynamic DOM rendering driven by API data
* `localStorage` used as a lightweight state layer

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/Ahmed-Mohamed-Abdelaziz-Nassar/Prayer-Times-And-Quran
cd Prayer-Times-And-Quran
```

Run locally:

```bash
# Open in browser
index.html
```

No build tools or dependencies required.

---

## 🔄 How It Works

* User opens the application
* Initial data is loaded
* Prayer times are fetched and rendered
* User navigates to Quran section
* Quran data is fetched dynamically
* State is optionally stored in `localStorage`

---

## 🔌 API Integration

### 🕰️ Prayer Times API

* Retrieves daily prayer schedule
* Uses asynchronous `fetch` requests
* Parses JSON into UI-ready data

### 📖 Quran API

* Fetches surahs and ayahs dynamically
* Injects content directly into the DOM

---

## 🎨 UI/UX Highlights

* Clean and minimal design focused on readability
* Responsive layout using Bootstrap
* Clear separation between functional sections
* Optimized for both desktop and mobile

---

## ⚡ Performance

* Lightweight (no frameworks)
* Minimal DOM re-rendering
* Efficient API calls
* Uses browser storage instead of heavy state libraries

---

## 🔐 Security

* No sensitive data stored
* Client-side API handling
* `localStorage` used only for non-sensitive data
* Basic input validation

---

## 🧩 Challenges & Solutions

### 📡 API Data Handling

**Challenge:** Inconsistent API response formats
**Solution:** Normalized response data before rendering

### 🧠 State Management

**Challenge:** Maintaining state across pages
**Solution:** Used `localStorage` as a lightweight state layer

### 🔗 Multi-Page Coordination

**Challenge:** Sharing logic between pages
**Solution:** Modular JavaScript structure

### ⚙️ Dynamic Rendering

**Challenge:** Updating UI without frameworks
**Solution:** Manual DOM manipulation with clear separation of concerns

---

## 📈 Future Improvements

* Add Geolocation API for automatic location detection
* Improve error handling and loading states
* Add dark mode
* Implement Quran search
* Add bookmarks / favorites
* Convert to SPA (React / Vue)
* Add PWA support

---

## 🌟 Why This Project Stands Out

* Real-world API-driven application
* Built بالكامل باستخدام Vanilla JavaScript
* Clean architecture and separation of concerns
* Practical and user-focused use case
* Strong demonstration of core front-end engineering skills

This is not a static project — it is a **functional, data-driven application**.

---

## 👨‍💻 Author

**Ahmed Mohamed Abdelaziz Nassar**
Frontend Developer | Software Engineering Portfolio

🔗 https://github.com/Ahmed-Mohamed-Abdelaziz-Nassar
🔗 https://www.linkedin.com/in/ahmed-mohamed-abdelaziz-nassar/
