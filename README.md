# 3D Interactive Portfolio - Anurag Sahu

![Project Status](https://img.shields.io/badge/Status-Active-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-black?style=flat&logo=three.js&logoColor=white)

A modern, "page-wise" personal portfolio website designed for a Data Analyst and Digital Cyber Crime Analyst. This project features a Single Page Application (SPA) feel without the need for frameworks, utilizing vanilla JavaScript for navigation and **Three.js** for an immersive, interactive 3D background.

## 🌟 Key Features

* **Interactive 3D Background:** A dynamic particle and geometric shape system built with Three.js that responds to mouse movement.
* **Page-Wise Navigation:** Unlike traditional scrolling sites, this portfolio uses a tab-based system to switch views instantly with a smooth fade-in animation.
* **Glassmorphism UI:** semi-transparent, blurred card designs that float above the 3D background.
* **Fully Responsive:** optimized layouts for desktop, tablet, and mobile devices.
* **Zero Dependencies:** No `npm install` required. The Three.js library is loaded via CDN.

## 📂 Project Structure

```text
/
├── index.html          # Main file containing HTML, CSS, and Logic
├── README.md           # Project documentation
└── assets/
    └── anu.jpg         # Profile picture (replace with your own)

🚀 How to Run

Since this is a static site, it is very easy to run locally.

    Clone or Download this repository.

    Add your Image: Place your profile picture in a folder named assets and name it anu.jpg, or update the src in index.html to point to your file.

    Open the file:

        Option A (Simplest): Double-click index.html to open it in your browser.

        Option B (Recommended): If you use VS Code, use the "Live Server" extension to launch the site. This mimics a real server environment.

🛠️ Customization Guide

All code (Structure, Style, and Script) is contained within index.html for simplicity. Here is how to edit specific parts:
1. Changing Personal Details

Search for the Home Section in the HTML:
HTML

<h1>Hey, <span class="hero-name">I’m [Your Name]</span></h1>
<h2 class="role-title">[Your Role]</h2>

2. Updating the Profile Picture

Locate the img tag in the #home section:
HTML

<img class="hero-photo" src="assets/your-photo.jpg" ... >

3. Modifying the 3D Background

Scroll down to the <script> tag at the bottom of the body. You can adjust:

    Colors: Look for const colors = [0x00f3ff, 0x00ff88, 0xbc13fe];

    Speed: Adjust values in the animate() function.

    Particle Count: Change const particleCount = 700;.

4. Adding/Removing Projects

Navigate to the <section id="projects">. The projects are organized in cards:
HTML

<div class="proj-card">
    <h3>Project Title</h3>
    <p>Description...</p>
    <div class="tags">...</div>
</div>

🎨 Color Palette

The site uses a dark, cyber-security themed palette:

    Background: #050a10 (Deep Dark Blue/Black)

    Text: #e0e6ed (Off-white)

    Accent 1 (Cyber): #00f3ff (Cyan)

    Accent 2 (Data): #00ff88 (Green)

📄 License

This project is free to use for personal portfolios.

Developed by Anurag Sahu

    LinkedIn

    GitHub
