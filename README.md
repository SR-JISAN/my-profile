<!-- Banner -->
<svg width="1200" height="350" viewBox="0 0 1200 350" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Gradient Animation -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00c6ff">
        <animate attributeName="stop-color"
          values="#00c6ff;#7f00ff;#00c6ff"
          dur="6s"
          repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#0072ff">
        <animate attributeName="stop-color"
          values="#0072ff;#ff0080;#0072ff"
          dur="6s"
          repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="10" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="350" rx="25" fill="url(#bg)" />

  <!-- Credit Card -->
  <g filter="url(#glow)">
    <rect x="80" y="70" rx="20" ry="20" width="420" height="230" fill="rgba(0,0,0,0.35)">
      <animateTransform attributeName="transform"
        type="translate"
        values="0 0; 0 -10; 0 0"
        dur="4s"
        repeatCount="indefinite"/>
    </rect>

    <text x="120" y="120" font-size="32" fill="white" font-weight="700">JISAN</text>
    <text x="120" y="150" font-size="16" fill="#ddd">MERN Stack Web Developer</text>

    <text x="120" y="200" font-size="20" fill="white" letter-spacing="3">
      1234 5678 9012 3456
    </text>

    <!-- Skill Icons -->
    <text x="120" y="245" font-size="22">⚛️</text>
    <text x="170" y="245" font-size="22">🟢</text>
    <text x="220" y="245" font-size="22">🍃</text>
    <text x="270" y="245" font-size="22">⚙️</text>
  </g>

  <!-- Right Side Info -->
  <text x="580" y="150" font-size="46" fill="white" font-weight="800">
    Hi, I'm Jisan 👋
  </text>

  <text x="580" y="190" font-size="22" fill="#f1f1f1">
    Building modern MERN stack applications
  </text>

  <text x="580" y="230" font-size="18" fill="#ddd">
    📍 Dhaka, Bangladesh
  </text>

  <text x="580" y="260" font-size="18" fill="#ddd">
    💻 React • Node • MongoDB • Express
  </text>
</svg>
>

<h1 align="center">Hi 👋, I'm Jisan</h1>
<h3 align="center">MERN Stack Web Developer</h3>

---

## 👨‍💻 About Me

I am a passionate **MERN Stack Web Developer** who loves building modern, scalable, and user-friendly web applications.  
I enjoy working with React, Node.js, and MongoDB to solve real-world problems.  
Always eager to learn new technologies and improve my development skills.

---

## 🚀 Current Activities

- 🌱 Exploring **Next.js**
- 🧑‍💻 Working on a **Tourism Website**
- 🔍 Improving performance and UI/UX in React projects
- 📚 Learning best practices for clean and maintainable code

---

## 🛠️ Skills

### 🎨 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap" />
</p>

### ⚙️ Backend
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,firebase" />
</p>

### 🧰 Tools & Others
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman" />
</p>

---

## 🌐 Connect With Me

<p>
  <a href="https://github.com/your-github-username" target="_blank">
    <img src="https://skillicons.dev/icons?i=github" />
  </a>
  <a href="https://www.linkedin.com/in/your-linkedin-username" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" />
  </a>
  <a href="https://twitter.com/your-twitter-username" target="_blank">
    <img src="https://skillicons.dev/icons?i=twitter" />
  </a>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=your-github-username&show_icons=true&theme=react" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username&layout=compact&theme=react" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=your-github-username&theme=react" />
</p>

---

⭐️ *Feel free to explore my repositories and connect with me!*
