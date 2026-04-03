# Prayer Times & Quran Web App

A production-ready front-end application that integrates real-time APIs to deliver accurate prayer schedules and Quran content through a clean, responsive, and scalable multi-page architecture.

---

## Overview

This project is a client-side web application designed to provide users with daily prayer times and Quran browsing functionality in a seamless and accessible interface.

The application consumes external APIs to deliver real-time religious data, while maintaining a lightweight architecture built entirely with Vanilla JavaScript. It demonstrates the ability to build structured, data-driven front-end systems without relying on modern frameworks.

---

## Live Demo

https://prayer-times-and-quran.netlify.app/

---

## Key Features

### Prayer Times

* Fetches real-time prayer times based on user location
* Displays a structured daily schedule
* Handles API response parsing and dynamic rendering

### Quran Integration

* Browse Quran content via external API
* Dynamic loading of surahs and ayahs
* Optimized reading interface for clarity and usability

### User Experience

* Multi-page navigation architecture
* Responsive layout across devices
* Smooth UI updates with minimal reloads

### Data Handling

* Lightweight state persistence using `localStorage`
* Efficient asynchronous API handling

---

## Tech Stack

### Languages

* HTML5
* CSS3
* JavaScript (Vanilla)

### Libraries

* Bootstrap

### APIs

* Prayer Times API
* Quran API

### Core Concepts

* REST API integration (`fetch`)
* Asynchronous JavaScript
* Client-side state management (LocalStorage)

---

## Architecture & Code Structure

```bash
/assets        → Static resources (images, icons)
/css           → Stylesheets and layout
/js            → Application logic (API + DOM handling)
/pages         → Feature-specific pages
index.html     → Entry point
```

### Architecture Highlights

* Clear separation between UI and logic layers
* Modular JavaScript structure for maintainability
* Dynamic DOM rendering driven by API data
* LocalStorage used as a lightweight state layer

---

## How It Works

1. User opens the application
2. Initial data is loaded on page initialization
3. Prayer times are fetched from the API
4. Data is parsed and rendered dynamically into the UI
5. User navigates to the Quran section
6. Quran data is fetched and displayed on demand
7. Application state is optionally persisted using `localStorage`

---

## Installation & Setup

```bash
git clone https://github.com/Ahmed-Mohamed-Abdelaziz-Nassar/Prayer-Times-And-Quran
cd Prayer-Times-And-Quran
```

Open `index.html` in your browser.

No build tools or dependencies required.

---

## API Integration

### Prayer Times API

* Retrieves daily prayer schedule
* Uses asynchronous `fetch` requests
* Parses JSON responses into UI-ready data

### Quran API

* Fetches surahs and ayahs dynamically
* Injects content directly into the DOM

### Data Handling

* Asynchronous operations with basic error handling
* UI updates triggered after successful data retrieval

---

## UI/UX Highlights

* Clean, minimal design focused on readability
* Responsive layout using Bootstrap
* Clear separation between functional sections
* Optimized for both desktop and mobile usage

---

## Performance Considerations

* Lightweight architecture (no frameworks)
* Minimal DOM re-rendering
* Efficient API usage
* Uses browser storage instead of heavy state libraries

---

## Security Considerations

* No sensitive data stored
* Client-side API handling
* LocalStorage used only for non-sensitive data
* Basic input validation where applicable

---

## Challenges & Solutions

### Handling External API Data

**Challenge:** Inconsistent API response formats
**Solution:** Normalized response data before rendering

### State Management Without Frameworks

**Challenge:** Maintaining state across multiple pages
**Solution:** Implemented LocalStorage as a lightweight state layer

### Multi-Page Coordination

**Challenge:** Sharing logic between pages
**Solution:** Modular JavaScript structure with reusable functions

### Dynamic Rendering

**Challenge:** Updating UI without frameworks
**Solution:** Manual DOM manipulation with clear separation of concerns

---

## Future Improvements

* Integrate Geolocation API for automatic location detection
* Improve error handling and loading states
* Add dark mode support
* Implement Quran search functionality
* Add bookmarks / favorites system
* Convert to SPA (React / Vue)
* Add offline support (PWA)

---

## Project Type

Front-End Engineering Project (Production-Oriented)

---

## Author

Ahmed Mohamed Abdelaziz Nassar

GitHub:
https://github.com/Ahmed-Mohamed-Abdelaziz-Nassar

LinkedIn:
https://www.linkedin.com/in/ahmed-mohamed-abdelaziz-nassar/
