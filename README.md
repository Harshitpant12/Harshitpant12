<!--## Hi there 
**Harshitpant12/Harshitpant12** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

 🌟 GitHub Profile README for Harshit Pant -->
<h1 align="center">Hi 👋, I'm Harshit Pant</h1>
<h3 align="center">Aspiring Software Developer | Full Stack Developer</h3>
<p align="center">"Turning ideas into code and challenges into opportunities 🚀"</p>
<p align="center"><a target="_blank" href="https://harshitpant.vercel.app" style="color:black" >Check Out My Portfolio!</a></p>

---

### 👨‍💻 About Me  
🎓 I'm pursuing **B.Tech in Computer Science & Engineering** from *Nanhi Pari Seemant Engineering Institute, Uttarakhand* (Batch 2026).  
💡 I’m passionate about **Software Development, and Full-Stack Development**.
🧠 Currently working on projects like **VantaWear - Premium Minimal Streetwear**, **Chummy - A Real-time Chat Application** and **NoteZipper - Note management Application**.
🚀 Always exploring new technologies and building real-world solutions.  

---

### 🛠️ Tech Stack  

#### 💻 Languages  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)

#### 🌐 Web Technologies  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![DOM](https://img.shields.io/badge/DOM-FF6F00?style=for-the-badge&logo=html5&logoColor=white)
![HTTP](https://img.shields.io/badge/HTTP-005C84?style=for-the-badge&logo=http&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)

#### 🧩 Frameworks & Libraries  
![ReactJs](https://img.shields.io/badge/-ReactJs-61DAFB?logo=react&logoColor=white&style=for-the-badge)
![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Nodemon](https://img.shields.io/badge/Nodemon-76d04b?style=for-the-badge&logo=nodemon&logoColor=white)


#### 🧰 Tools & IDEs  
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

#### 🗄️ Databases  
![SQL](https://img.shields.io/badge/SQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b?style=for-the-badge&logo=mongodb&logoColor=white)

---

### 🚀 Featured Projects  

### SkillSync - AI-Powered ATS Optimizer & Microservices Architecture

**SkillSync** is a full-stack SaaS platform designed to calculate Applicant Tracking System (ATS) compatibility scores. Utilizing a decoupled microservices architecture, it isolates a primary MERN-stack server from a dedicated Python NLP engine to process compute-heavy document parsing and cosine-similarity algorithms without blocking the main event loop.

**Tech Used:** MongoDB, Express.js, React.js, Node.js, Python (Flask), spaCy, scikit-learn, Google Gemini API, Tailwind CSS, Google OAuth 2.0, JSON Web Tokens, Vercel, Render

**Features**
* **Microservices Architecture:** Independently deployed Node.js REST API on Vercel and a Python/Flask NLP engine on Render for optimized CPU load balancing.
* **Advanced NLP Pipeline:** Leverages `pdfminer.six` for high-fidelity text extraction, utilizing `spaCy` and `scikit-learn` to calculate vector similarities between resumes and job descriptions in under 15 seconds.
* **Enterprise-Grade Authentication:** Built a robust JWT system with silent refresh interceptors, cross-domain HTTP-only cookies, and seamless Google OAuth 2.0 integration via Google Identity Services.
* **Context-Aware AI Suggestions:** Integrated the Google Gemini API to dynamically generate targeted resume improvement suggestions based on the NLP engine's output.
* **Dynamic Client Dashboard:** Engineered a responsive React/Vite frontend using Tailwind CSS and Framer Motion, featuring drag-and-drop file uploads and silent background service wake-ups to mask cold-start latency.
* **High-Performance Routing:** Load-tested using Apache JMeter, optimizing CORS configurations and payload routing to maintain sub-400ms average response times under concurrent loads.

📂 [View Project Repository](https://github.com/Harshitpant12/skillsync) | 🌐 [Visit Now](https://skillsync-official.vercel.app)

### VantaWear – Serverless MERN E-Commerce Architecture
VantaWear is a premium, full-stack e-commerce platform built with the MERN stack. Designed with a brutalist aesthetic, it features secure JWT authentication, real-time Stripe payment webhooks, an interactive admin analytics dashboard, and a serverless architecture deployed on Vercel's edge network.

**Tech Used**: MongoDB, Express.js, React.js, Node.js, Tailwind CSS, Stripe API, JSON Web Tokens, Vite, Vercel Serverless

### Features

- **Serverless Architecture**: Deployed as an optimized monorepo on Vercel utilizing Serverless Functions and custom routing rules.
- **Fault-Tolerant Checkout**: Integrated Stripe Elements with background webhook verification to ensure orders are created even if the client disconnects.
- **Advanced Authentication**: Built a custom JWT system with secure, cross-domain cookies utilizing reverse proxy configurations.
- **Real Time Admin Analytics**: Implemented a protected dashboard using Recharts to visualize revenue flow and track live order statuses.
- **State Management**: Utilized React Context API for global cart state and user session persistence across the application.
- **Responsive UI/UX**: Built a mobile-first, highly accessible frontend utilizing Tailwind CSS for a premium, heavy-weight streetwear aesthetic.

📂 [View Project Repository](https://github.com/Harshitpant12/VantaWear)
🌐 [Visit Now](https://vantawear.vercel.app/)

## Chummy – Real-Time Social Chat Platform (MERN)

Chummy is a full-stack real-time chat platform built using the MERN stack, designed for seamless communication between users. The application features secure authentication, instant messaging powered by WebSockets, and a modern responsive interface. It focuses on delivering fast, scalable, and user-friendly messaging with persistent conversations and smooth UI interactions.

**Tech Used:** MongoDB, Express.js, React.js, Node.js, Socket.io, JSON Web Tokens, Tailwind CSS, Zustand, Axios, Cloudinary

### Features

- **Real-Time Messaging:**  
Implemented instant bidirectional communication using Socket.io, allowing users to send and receive messages without page refresh.
- **Secure Authentication:**  
Built JWT-based authentication with HTTP-only cookies to securely manage user sessions and protect private routes.
- **Online User Presence:**  
Tracks active users in real time and displays online/offline status using WebSocket connections.
- **Media Sharing:**  
Integrated Cloudinary to enable users to send images in chats with optimized storage and delivery.
- **Global State Management:**  
Used Zustand to efficiently manage global states such as user sessions, conversations, and message updates.
- **Responsive Chat Interface:**  
Developed a clean, mobile-friendly UI using Tailwind CSS with modern chat layouts and smooth user interactions.

📂 [View Project Repository](https://github.com/Harshitpant12/chummy-chat)  
🌐 [Visit Now](https://chummy.onrender.com)

### NoteZipper – Full-Stack Note-Taking Application
A modern, full-stack note-taking web application that allows users to create, edit, organize, and manage their notes efficiently. NoteZipper provides a smooth and intuitive user experience with secure data handling and real-time interactions between the frontend and backend.

**Tech Used**: React.js, Node.js, Express.js, MongoDB, Tailwind CSS, DaisyUi

### Features

- Full-stack architecture with React frontend and Node.js + Express backend
- RESTful APIs for creating, reading, updating, and deleting notes
- Axios used on the frontend for seamless communication with backend APIs
- Backend structured using Express routes and controllers
- MongoDB for efficient and scalable data storage
- Clean, responsive UI for easy note management

📂 [View Project Repository](https://github.com/Harshitpant12/NoteZipper)
🌐 [Visit Now](https://notezipper-g8e3.onrender.com/)


---

### 📊 GitHub Stats  
[![GitHub Streak](https://github-readme-streak-stats-nu-snowy.vercel.app?user=harshitpant12&theme=tokyonight&border_radius=10&short_numbers=true)](https://git.io/streak-stats)

---



### 🤝 Connect With Me  

<p align="center">
  <a href="https://www.linkedin.com/in/harshitpant12/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:harshpant778@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/Harshitpant12" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
 <a href="https://leetcode.com/u/harshitpant_1" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
</p>

---

⭐️ *“Code. Learn. Improve. Repeat.”*
