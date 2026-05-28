# Hey there! I'm Bohdan Betskov 👋

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=007ACC&center=true&vCenter=true&width=700&height=50&lines=Backend+Developer+%7C+Python+%2F+Node.js;Automation+%26+DevOps+Engineer;IoT+Networking+%26+Real-time+WebRTC;Building+Fault-Tolerant+ETL+Pipelines" alt="Typing SVG" />
</div>

<p align="center">
  <b>Python / Node.js Backend Developer | Automation & DevOps Engineer</b><br>
  📍 Vinnitsya, Ukraine (Open to Relocation & Remote)<br>
  📧 <a href="mailto:beckovbogdan@gmail.com">beckovbogdan@gmail.com</a> | 📞 +380973031674
</p>

<p align="center">
  <a href="https://linkedin.com/in/bohdan-betskov-569327405/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.fiverr.com/kamedashe"><img src="https://img.shields.io/badge/Fiverr-Hire%20Me%20(Freelance)-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white" alt="Fiverr" /></a>
  <a href="https://t.me/dreamotearz"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://github.com/kamedashe"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

> [!IMPORTANT]
> 💼 **Available for Freelance & Custom Projects!**
> You can view my services, order a custom gig, or contact me directly on my [**Fiverr Profile (kamedashe)**](https://www.fiverr.com/kamedashe). Let's build something great together!

---

## ⚡ About Me

> Performance-driven Backend Developer and Automation Engineer with deep expertise in Python, Node.js, and Linux systems architecture. Specializing in designing fault-tolerant ETL pipelines, developing low-level hardware networking solutions for IoT devices (Raspberry Pi, NVIDIA Jetson), automating complex browser workflows (Playwright), and integrating real-time communication protocols (WebRTC, Socket.io). Focused on engineering secure, scalable, and high-performance backend systems.

---

## 🛠️ Technical Stack & Toolkit

<div align="center">

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Bash](https://img.shields.io/badge/Shell_Script-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) |
| **Automation & Data** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![GeoPandas](https://img.shields.io/badge/GeoPandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |
| **Real-time & Network** | ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white) |
| **DevOps & Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Heroku](https://img.shields.io/badge/Heroku-430098?style=flat-square&logo=heroku&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Frontend UI** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |

</div>

---

## 📂 Featured Projects & Experience

### 🔒 Hardened Linux Captive Portal `IoT / Jetson / RPi`
*Engineered a lightweight, hardware-level Captive Portal networking architecture for Linux IoT deployments to mitigate driver and hardware constraints.*
* **Low-Level Isolation:** Bypassed NetworkManager constraints using `hostapd` and `dnsmasq` daemons, eliminating OS D-Bus crashes and guaranteeing 100% access point stability during internet drops.
* **Orchestration Logic:** Created a robust daemon system in Bash and Flask to seamlessly transition devices between Client and Access Point modes while capturing credentials safely.
* **Commercial Success:** Successfully productized the solution as a top-rated service on [Fiverr](https://www.fiverr.com/kamedashe), provisioning hardened standalone OS images for Raspberry Pi Lite and NVIDIA Jetson.
* **Tech Stack:** `Python` `Flask` `Bash Scripting` `hostapd` `dnsmasq` `HTML/JS` `Linux`

### ✈️ Avia Navigation Data Pipeline & Admin API `Data Engineering`
*Designed an enterprise-grade data processing engine automating the acquisition, validation, and spatial optimization of FAA aeronautical datasets.*
* **Robust Scraping & API:** Built an asynchronous REST API using FastAPI alongside an intelligent data scraper equipped with isolated error-handling blocks to prevent complete pipeline failures.
* **Spatial Optimization:** Automated geodata cleanup and optimization using Pandas and GeoPandas, paired with a custom storage manager that auto-purges corrupted/outdated datasets.
* **Glassmorphism Admin UI:** Implemented a modern dashboard with Tailwind CSS for real-time task status tracking, remote scraping triggers, and historical log monitoring.
* **Tech Stack:** `Python 3.10+` `FastAPI` `Pandas` `GeoPandas` `Docker` `Tailwind CSS` `Telegram Bot API`

### 🤖 Goszakup Tender Bot ("Two Brothers" Architecture) `Automation / QA`
*Created a high-speed automated system designed for persistent session monitoring and rapid application submission on the national trade procurement platform.*
* **Decoupled Architecture:** Built a dual-script setup: a background daemon (`auth_keeper.py`) running continuously to prevent session timeouts and write cookies to cache, and a high-speed sniper (`main.py`) to instantly load active cookies and file requests.
* **Anti-Bot Bypass:** Leveraged Playwright to build advanced browser workflows that bypass rigid anti-bot patterns and maintain state persistence.
* **Cryptographic Integration:** Configured automated document workflows by interfacing directly with a containerized cryptographic service node (`NCANode`) via Docker for programmatic EDS (Electronic Digital Signature) signing.
* **Tech Stack:** `Python` `Playwright` `Docker` `NCANode` `YAML` `File Caching`

### 🗣️ Anonymous Voice Chat Roulette `Fullstack Node.js / WebRTC`
*Developed a high-performance anonymous voice communication platform embedded entirely inside a Telegram Mini App using peer-to-peer real-time technology.*
* **Signaling Hub:** Developed a Node.js and Express backend server utilizing Socket.io as a scalable, event-driven signaling hub for instant client handshakes.
* **Matching Algorithm:** Engineered a randomized pairing algorithm featuring granular matching logic based on gender and age inputs.
* **P2P Audio:** Implemented low-latency peer-to-peer audio streams with WebRTC, routing heavy traffic directly between clients to drastically lower backend processing costs.
* **Tech Stack:** `Node.js` `Express` `Socket.io` `WebRTC` `Node-Telegram-Bot-API` `Heroku`

---

## 🎓 Education & Languages

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎓 Education</h3>
      <p><b>Odesa Polytechnic National University</b><br>
      <i>Bachelor of Science in Software Engineering</i><br>
      📅 2023 — 2027</p>
    </td>
    <td width="50%" valign="top">
      <h3>🗣️ Languages</h3>
      <ul>
        <li><b>English:</b> B2 (Upper-Intermediate — Proficient in tech documentation, logging, and written communication)</li>
        <li><b>Russian:</b> Native</li>
        <li><b>Ukrainian:</b> Fluent</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📊 Github Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kamedashe&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kamedashe&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</div>

<p align="center">
  <img src="https://profile-counter.glitch.me/kamedashe/count.svg" alt="Visitor Counter" />
</p>
