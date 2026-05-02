# Kunal Rajan Bhatia - Personal Portfolio

A modern, terminal-inspired personal portfolio website built with Vanilla HTML, CSS, and JavaScript. The project is designed to be lightweight, responsive, and easily maintainable through a central JSON data file.

![Portfolio Preview](me.png)

## 🚀 Features

- **Terminal Aesthetic:** A unique UI inspired by terminal interfaces, featuring syntax highlighting colors and a command-line feel.
- **Dark/Light Mode:** Full support for system-preferred and manual theme switching.
- **Data-Driven:** All content (bio, skills, projects, experience) is loaded dynamically from `data.json`.
- **Responsive Design:** Optimized for all screen sizes, from mobile to ultra-wide displays.
- **Animations:** Smooth scroll-reveal animations and interactive terminal elements.
- **Performant:** Zero external dependencies (other than Google Fonts), leading to fast load times.

## 🛠️ Tech Stack

- **HTML5:** Semantic structure.
- **CSS3:** Custom properties (CSS variables), Flexbox, Grid, and standard animations. No utility frameworks or preprocessors.
- **JavaScript (ES6+):** Pure Vanilla JS for DOM manipulation, data fetching, and interactive behaviors.
- **JSON:** Content management and configuration.

## 📦 Getting Started

### Local Development

Since the site fetches `data.json` using the Fetch API, it requires a local server to avoid CORS issues when opening the file directly.

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/myportfolio.git
    cd myportfolio
    ```

2.  Run a local server:
    Using Python:
    ```bash
    python -m http.server 8000
    ```
    Or using Node.js `serve` or `live-server`:
    ```bash
    npx serve .
    ```

3.  Open your browser and visit `http://localhost:8000`.

## ⚙️ Customization

To update the portfolio with your own information:

1.  Open `data.json`.
2.  Modify the fields under `meta`, `hero`, `about`, `skills`, `projects`, `experience`, etc.
3.  Replace `me.png` with your own profile image.
4.  Replace `RESUME_KUNAL_BHATIA.pdf` with your own resume and update the filename in `data.json` under `meta.resumeFile`.

## 📂 Project Structure

- `index.html`: The main entry point and single-page structure.
- `data.json`: The source of truth for all content.
- `me.png`: Profile image used in the hero section.
- `RESUME_KUNAL_BHATIA.pdf`: The downloadable resume file.
- `CSS` & `JS`: Inlined within `index.html` for maximum portability and performance.

---

Crafted with ☕ and caffeine by [Kunal Rajan Bhatia](https://www.linkedin.com/in/kunal-r-bhatia).
