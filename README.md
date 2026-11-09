# Personal Portfolio Web Application 👤

<div align="center">

[![Live Demo](https://img.shields.io/badge/Demo-Live_Website-4C0827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rpprudenciado.github.io/Personal-Portfolio-Web-Application/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Flexbox](https://img.shields.io/badge/FLEXBOX-563D7C?style=for-the-badge)](#)
[![UI/UX](https://img.shields.io/badge/UI%2FUX-4B4B4B?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

> *A multi-page responsive personal portfolio website built with semantic HTML5 and modern CSS3, demonstrating core CSS layout techniques, Box Model principles, and Flexbox alignment.*

</div>

---

## 📌 Project Overview

This multi-page web application serves as a personal profile and professional portfolio for **Rhona-Mae Prudenciado**, a BSIT student at Asia Pacific College specializing in Cloud Computing. The website was developed from scratch to showcase key front-end concepts—specifically focusing on the **CSS Box Model** (padding, margins, borders, box-sizing) and modern **Flexbox** positioning.

### 🌐 Live Demo
🔗 **Visit the Live Website:** [https://rpprudenciado.github.io/Personal-Portfolio-Web-Application/](https://rpprudenciado.github.io/Personal-Portfolio-Web-Application/)

### 📄 Pages Included

1. **Home (`index.html`)** – Features a hero section with a profile picture, tagline, location, bio section, and an "At a Glance" summary grid.
2. **Skills (`skills.html`)** – Outlines technical skills, Python coursework (DataCamp), web development, CSS training, and professional soft skills formatted with Flexbox card rows and custom pill lists.
3. **Projects (`projects.html`)** – Displays real-world projects with links to GitHub repositories (*Navig8.tech*, *Java Banking System*, *MotoPulse*, and *Personal Portfolio Website*).
4. **Contact (`contact.html`)** – Displays direct communication links (LinkedIn, GitHub, Email, Taguig City location) along with interactive call-to-action buttons.

---

## ✨ Activity Requirements & Verification

This project fulfills all criteria set in **Activity 2: CSS (Box Model & FlexBox)**:

| Requirement | Implementation Detail | Location in Code |
| :--- | :--- | :--- |
| **1. 3 Types of CSS** | • **External CSS:** Maintained in `style.css` for site-wide styling, CSS variables (`:root`), and global resets.<br>• **Internal CSS:** Embedded `<style>` tags in `skills.html` for card text alignment.<br>• **Inline CSS:** Applied via `style=""` attributes in `index.html` and `contact.html` for custom typography and spacing. | • `style.css`<br>• `skills.html` (`<head>`)<br>• `index.html`, `contact.html` |
| **2. Profile Page** | Comprehensive home section highlighting education, background, focus areas, and portrait image. | `index.html` |
| **3. List of Skills** | Categorized display of Python, Java, Bash, HTML, CSS, Computer Systems Servicing, and soft skills using flexible tag components (`.pill-list`). | `skills.html` |
| **4. Contact Card** | Double-card setup featuring direct outreach buttons (LinkedIn & Email) alongside detailed contact information. | `contact.html` |
| **5. At least 3 Pages** | Exceeds requirement with **4 distinct HTML pages**: Home, Skills, Projects, and Contact. | `index.html`, `skills.html`, `projects.html`, `contact.html` |
| **6. Creativity & Styling** | Custom dark crimson/violet theme palette with responsive flexbox design and hover interactions. | `style.css` |

---

## 🎨 Design System & Color Palette

The project utilizes CSS Custom Properties (`:root`) for cohesive color application:

* `--coffee-bean` (`#100007`) – Main navigation & footer background
* `--midnight-violet` (`#200116`) – Hero & header gradient base
* `--rich-mahogany` (`#2D0605`) – Primary text color
* `--crimson-violet` (`#4C0827`) – Accent color, borders, and main buttons
* `--soft-linen` (`#E6EBE0`) – Page background and high-contrast text

---

## 📁 Repository Structure

```
.
├── index.html                  # Home / Profile Page
├── skills.html                 # Technical & Professional Skills Page
├── projects.html               # Projects & GitHub Links Page
├── contact.html                # Contact Card & Outreach Page
├── style.css                   # Main External Stylesheet
├── PORTFOLIO PICTURE 1.2.jpg   # Profile Photo Asset
├── LICENSE                     # MIT License
└── README.md                   # Project Documentation
```

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rpprudenciado/Personal-Portfolio-Web-Application.git
   ```
2. **Navigate into the directory:**
   ```bash
   cd Personal-Portfolio-Web-Application
   ```
3. **Open in Browser:**
   * Double-click `index.html` to launch in any standard browser.
   * Or use Visual Studio Code's **Live Server** extension (`npx live-server .`).

---

## 📝 Activity Deliverables Summary

* **HTML files:** `index.html`, `skills.html`, `projects.html`, `contact.html`
* **CSS file:** `style.css` (plus internal & inline CSS across pages)
* **Image asset:** `PORTFOLIO PICTURE 1.2.jpg`
* **License:** MIT

---

## 👤 Author

**Rhona-Mae Prudenciado**  
*BSIT Student, Asia Pacific College*  
GitHub: [@rpprudenciado](https://github.com/rpprudenciado) • Email: [prudenciadorhonamae@gmail.com](mailto:prudenciadorhonamae@gmail.com)
