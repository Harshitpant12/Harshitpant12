<h1 align="center">Hi 👋, I'm Harshit Pant</h1>
<h3 align="center">Aspiring Software Developer | Full Stack Engineer | Problem Solver</h3>

<p align="center">
  <i>"Turning ideas into code and challenges into opportunities 🚀"</i>
</p>

<p align="center">
  <a target="_blank" href="https://harshitpant.vercel.app"><b>🌐 Check Out My Portfolio</b></a>
</p>

---

### 👨‍💻 About Me  

🎓 Pursuing a **B.Tech in Computer Science & Engineering** (Batch 2026).  
💡 Passionate about **Full-Stack Web Development (MERN)** and building production-grade, highly scalable applications.  
🧠 Currently sharpening my skills in **Data Structures, Algorithms (DSA), and Problem Solving** to write clean, optimized code.  
🚀 Actively building real-world solutions like **VantaWear**, **SkillSync**, and **Chummy** using decoupled microservices and serverless architectures.  
🌱 Always eager to explore new technologies, tackle complex architectural challenges, and optimize backend performance.

---

### 🛠️ Tech Stack & Tools  

#### 💻 Languages  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

#### 🌐 Web Technologies & Core  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![DOM](https://img.shields.io/badge/DOM-FF6F00?style=for-the-badge&logo=html5&logoColor=white)
![HTTP](https://img.shields.io/badge/HTTP-005C84?style=for-the-badge&logo=http&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)

#### 🧩 Frameworks & Libraries  
![ReactJs](https://img.shields.io/badge/-ReactJs-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

#### 🗄️ Databases  
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b?style=for-the-badge&logo=mongodb&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

#### 🧰 Tools & Platforms  
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

### 🚀 Featured Projects  

#### [SkillSync](https://skillsync-official.vercel.app) — NLP-Driven ATS Matching Engine & Scoring Platform
A full-stack SaaS platform designed to calculate Applicant Tracking System (ATS) compatibility scores. Utilizing a decoupled microservices architecture, it isolates a primary MERN-stack server from a dedicated Python NLP engine to process compute-heavy document parsing and cosine-similarity algorithms without blocking the main event loop.
* **Microservices Architecture:** Independently deployed Node.js REST API on Vercel and a Python/Flask NLP engine on Render for optimized CPU load balancing.
* **Advanced NLP Pipeline:** Leverages `pdfminer.six` for high-fidelity text extraction, utilizing `spaCy` and `scikit-learn` to calculate vector similarities between resumes and job descriptions in under 15 seconds.
* **Enterprise-Grade Authentication:** Built a robust JWT system with silent refresh interceptors, cross-domain HTTP-only cookies, and seamless Google OAuth 2.0 integration via Google Identity Services.
* **Context-Aware AI Suggestions:** Integrated the Google Gemini API to dynamically generate targeted resume improvement suggestions based on the NLP engine's output.
* **Dynamic Client Dashboard:** Engineered a responsive React/Vite frontend using Tailwind CSS and Framer Motion, featuring drag-and-drop file uploads and silent background service wake-ups to mask cold-start latency.
* **High-Performance Routing:** Optimized CORS configurations and payload routing to maintain sub-400ms average response times under concurrent loads.

📂 [Repository](https://github.com/Harshitpant12/skillsync) | 🌐 [Live Demo](https://skillsync-official.vercel.app)

<br/>

#### [VantaWear](https://vantawear.vercel.app/) — Serverless MERN E-Commerce Architecture
A premium, full-stack e-commerce platform built with a brutalist aesthetic. Designed for seamless UX, it features secure authentication, real-time webhooks, an interactive admin analytics dashboard, and a serverless architecture deployed on Vercel's edge network.
* **Serverless Architecture:** Deployed as an optimized monorepo on Vercel utilizing Serverless Functions and custom routing rules.
* **Fault-Tolerant Checkout:** Integrated Stripe Elements with background webhook verification to ensure orders are reliably processed even during client disconnects.
* **Advanced Authentication:** Built a custom JWT system with secure, cross-domain cookies utilizing reverse proxy configurations.
* **Real-Time Admin Analytics:** Implemented a protected dashboard using Recharts to visualize revenue flow and track live order statuses.
* **Premium UI/UX:** Built a highly accessible, mobile-first frontend utilizing Tailwind CSS and the React Context API for global state persistence.

📂 [Repository](https://github.com/Harshitpant12/VantaWear) | 🌐 [Live Demo](https://vantawear.vercel.app/)

<br/>

#### [Chummy](https://chummy.onrender.com) — Real-Time Social Chat Platform
A full-stack instant messaging platform focused on delivering fast, scalable, and user-friendly communication with persistent conversations and clean UI interactions.
* **Real-Time Messaging:** Implemented bidirectional communication using Socket.io for seamless messaging without page refreshes.
* **Live Status & Media:** Tracks active user presence via WebSockets and integrates Cloudinary for optimized image storage and delivery.
* **Secure Sessions:** JWT-based authentication with HTTP-only cookies to securely manage user sessions and guard protected routes.
* **State & UI:** Utilized Zustand for efficient global state management alongside a clean, responsive layout built with Tailwind CSS.

📂 [Repository](https://github.com/Harshitpant12/chummy-chat) | 🌐 [Live Demo](https://chummy.onrender.com)

<br/>

#### [NoteZipper](https://notezipper-g8e3.onrender.com/) — Full-Stack Note Management System
A modern web application built to create, edit, organize, and securely manage personal notes efficiently.
* Engineered full-stack RESTful APIs utilizing Express controllers and MongoDB for highly scalable data storage.
* Implemented clean frontend-backend synchronization using Axios, styled fully with Tailwind CSS and DaisyUI.

📂 [Repository](https://github.com/Harshitpant12/NoteZipper) | 🌐 [Live Demo](https://notezipper-g8e3.onrender.com/)

---

### 📊 GitHub Stats  

<p align="center">
  <a href="https://git.io/streak-stats">
    <img src="https://github-readme-streak-stats-nu-snowy.vercel.app?user=harshitpant12&theme=tokyonight&border_radius=10&short_numbers=true" alt="GitHub Streak" />
  </a>
</p>

---

### 🤝 Connect With Me  

<p align="center">
  <a href="https://www.linkedin.com/in/harshitpant12/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://leetcode.com/u/harshitpant_1" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
  <a href="https://github.com/Harshitpant12" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:harshpant778@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
</p>

<p align="center">
  ⭐️ <i>“Code. Learn. Improve. Repeat.”</i>
</p>
