# Islamic Learning Center

A modern, responsive Single Page Application (SPA) designed to serve as an Islamic E-learning platform. Developed to deliver educational content—including video lectures and supplementary presentations—with a sleek, user-friendly interface.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Contact](#contact)

---

## Overview
The **Islamic Learning Center** project is an interactive platform built to streamline the delivery of introductory Islamic educational materials. Specifically tailored for an overarching 15-topic curriculum, it allows users to navigate linearly through topics or select specific lessons via an accessible dropdown menu.

## Key Features
- **Centralized Learning Materials:** Integrating YouTube embedded videos and Google Drive slide presentations directly into the platform.
- **Dynamic Content Navigation:** Transition between topics seamlessly using directional buttons, bullet pagination dots, or a dropdown selection menu without triggering page reloads.
- **Responsive "Antigravity" UI:** A modern interface utilizing Tailwind CSS, featuring subtle floating hover effects, floating shadows, glassmorphism-inspired elements, and a clean typography hierarchy. 
- **Accessible Document Downloads:** Dedicated download links for PDF presentation files.
- **Web Share API Integration:** A native share button functionality permitting users to easily disseminate lesson links on compatible devices.

## Technologies Used
- **HTML5:** Core architectural structure.
- **Vanilla JavaScript (ES6+):** For application logic, state management, and DOM manipulation.
- **Tailwind CSS (via CDN):** Rapid, utility-first styling tailored with a customized color palette (`islamic-green`, `islamic-gold`, `off-white`).
- **Google Fonts (Sarabun):** Specialized typography supporting the Thai language efficiently.
- **FontAwesome:** Scalable vector icons.

## Project Structure
The entire application is consolidated into a single entry file to maximize simplicity and optimize static site hosting. Data objects representing course materials (such as video IDs, document links, and titles) reside within the local JavaScript variables to allow straightforward maintenance and scalability.

## Deployment
This application is designed specifically as a static asset, making it perfectly suited for out-of-the-box hosting environments such as **GitHub Pages**, **Cloudflare Pages**, or standard Apache/Nginx web servers. No backend processing, building steps, or database connectivity are required. 
Simply host the `index.html` file in the root directory.

## Contact
For inquiries regarding development or maintenance, please reach out to the project developer:
- **Email:** [Abdulloh.eg@gmail.com](mailto:Abdulloh.eg@gmail.com)
