# Doinik Bangla Kagoj - Professional News Portal

**Doinik Bangla Kagoj** is a feature-rich, responsive news application designed to provide a seamless reading experience across all devices. It includes advanced functionalities like real-time search, category filtering, a dynamic breaking news ticker, and a complete administrative dashboard for news creation and management.

## 🚀 Key Features

### 📰 Content Management

* **Dynamic News Grid:** Automatically renders news cards with titles, categories, images, and timestamps.
* **Trending Carousel:** A high-visibility slider on the homepage showcasing the five most recent or popular stories.
* **Breaking News Ticker:** A customizable scrolling marquee at the top of the page. Admins can update the text and adjust the scroll speed in real-time.
* **Pagination:** Efficiently handles large volumes of news by splitting content into digestible pages.

### 🛠 Administrative Tools

* **Secure Admin Login:** Access restricted features using specialized credentials.
* **News Editor:** Create, edit, and delete news articles directly from the UI. Supports image uploads via `FileReader` API.
* **Ticker Control:** Dedicated modal to modify breaking news content and animation duration.

### 👤 User Experience

* **Dark Mode:** A fully integrated dark/light theme toggle that persists across sessions using `localStorage`.
* **Interactive Comments:** Logged-in users can engage with news stories through a dedicated comment section.
* **Advanced Filtering:** * Search news by keywords.
* Filter by categories (Politics, Tech, Sports, etc.).
* **Date Range Filtering:** Find news published between specific dates.
* Sort by "Latest" or "Oldest."


* **Responsive Design:** Optimized for mobile, tablet, and desktop views with a sleek "hamburger" sidebar menu.

### 🔒 Security & Performance

* **Form Validation:** Ensures all required fields are met before submission.
* **Toast Notifications:** Real-time feedback for user actions (e.g., "Message Sent," "Login Successful").
* **Performance:** Implements debouncing on search inputs and lazy-loading principles for a smooth UI.

---

## 🛠 Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Variables/Flexbox/Grid), Vanilla JavaScript (ES6+).
* **Icons & Fonts:** FontAwesome 6.0, Google Fonts (Roboto).
* **Data Persistence:** `localStorage` (simulates a database for news items, user accounts, and theme preferences).

---

## 📂 Project Structure

* `index.html`: The main portal featuring the news grid, carousel, and search tools.
* `contact-us.html`: A functional contact page with a validated message form.
* `rules.html`: Community guidelines and site policies.
* `styles.css`: Centralized stylesheet containing modern CSS variables and dark mode logic.
* `DBK.png/jpg`: Official branding and logo assets.

---

## 🚦 Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/doinik-bangla-kagoj.git

```


2. **Open the project:**
Simply open `index.html` in any modern web browser.
3. **Admin Access:**
* **Username:** `admin`
* **Password:** `password123`

