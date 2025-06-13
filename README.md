# 📺 Enhanced EPG Viewer 🚀

A sleek, fast, and modern Electronic Program Guide (EPG) viewer built with pure HTML, CSS, and JavaScript. Get real-time TV schedules for popular Indian DTH providers with a beautiful, responsive interface inspired by Google's Material Design.



---

## ✨ Features

-   **Multiple EPG Sources** 📡: Seamlessly switch between different EPG providers (e.g., TATA PLAY, TSAIO, JioTV).
-   **Blazing Fast** ⚡: Utilizes vanilla JavaScript and efficient data parsing for a snappy user experience.
-   **Dynamic Search & Sort** 🔍: Instantly find any channel with a real-time search filter and sort channels alphabetically.
-   **Live Program Info** 🔴:
    -   See "Now Playing" and "Next" programs directly on the channel cards.
    -   A dedicated "Now Playing" section with a **live, updating progress bar** and a blinking "live" indicator.
-   **Full Channel Schedule** 📅:
    -   View a channel's complete schedule on the same page (no new tabs!).
    -   Programs are automatically categorized into **Upcoming** and **Catch-up (Recently Aired)**.
    -   Clear date headers for easy navigation through multi-day schedules.
-   **Stunning UI/UX** 🎨:
    -   Modern interface inspired by Google's Material Design.
    -   Satisfying **ripple click effects** on all interactive elements.
    -   Smooth animations and hover effects for a premium feel.
    -   Fully responsive design for a great experience on desktop, tablets, and mobile.
-   **Smart Caching** 🧠: EPG data is cached per session to reduce load times and API calls when switching between sort orders or views.


---

## 🛠️ Tech Stack

-   **HTML5**
-   **CSS3** (with CSS Variables for easy theming)
-   **Vanilla JavaScript (ES6+)**
-   **[Pako.js](https://github.com/nodeca/pako)**: For high-performance GZIP decompression in the browser.

---

## 🚀 Getting Started

No complex setup is required! Since this is a vanilla HTML/CSS/JS project, you can run it directly.

### Option 1: Live Demo (Deploy with Vercel)

Click the button below to deploy your own instance of the EPG Viewer to Vercel in seconds.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2F<YOUR_USERNAME>%2F<YOUR_REPOSITORY_NAME>)

> **Note:** Remember to replace `<YOUR_USERNAME>` and `<YOUR_REPOSITORY_NAME>` in the link above before sharing!

### Option 2: Running Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/<YOUR_USERNAME>/<YOUR_REPOSITORY_NAME>.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <YOUR_REPOSITORY_NAME>
    ```
3.  **Open the `index.html` file:**
    -   Simply double-click the `index.html` file in your file explorer to open it in your favorite web browser.
    -   *Alternatively*, for the best experience (especially with fetch requests), run a simple local server. If you have Python installed:
        ```bash
        # For Python 3
        python -m http.server
        ```
        Then, open your browser and go to `http://localhost:8000`.

---

## 🖼️ Screenshots

| Channel Grid View                                     | Full Schedule View                                 |
| ------------------------------------------------------- | ---------------------------------------------------- |
|  |  |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/<YOUR_USERNAME>/<YOUR_REPOSITORY_NAME>/issues).

---

## ❤️ Show your support

Give a ⭐️ if this project helped you!

---
