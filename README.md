<!-- HEADER ANIMADO SVG - 100% propio, sin servicios externos -->
<div align="center">

<svg width="100%" viewBox="0 0 860 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0f1923"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="line1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#58a6ff;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#58a6ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#58a6ff;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="line2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#1f6feb;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#1f6feb;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#1f6feb;stop-opacity:0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Fondo -->
  <rect width="860" height="220" fill="url(#bg)" rx="12"/>

  <!-- Grid de puntos de fondo -->
  <g opacity="0.15">
    <circle cx="50" cy="30" r="1.5" fill="#58a6ff"><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite" begin="0s"/></circle>
    <circle cx="150" cy="20" r="1" fill="#58a6ff"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" repeatCount="indefinite" begin="0.5s"/></circle>
    <circle cx="250" cy="40" r="1.5" fill="#1f6feb"><animate attributeName="opacity" values="0.1;0.7;0.1" dur="2.5s" repeatCount="indefinite" begin="1s"/></circle>
    <circle cx="350" cy="15" r="1" fill="#58a6ff"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.5s" repeatCount="indefinite" begin="0.3s"/></circle>
    <circle cx="450" cy="35" r="1.5" fill="#1f6feb"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="2s" repeatCount="indefinite" begin="1.2s"/></circle>
    <circle cx="550" cy="25" r="1" fill="#58a6ff"><animate attributeName="opacity" values="0.1;0.6;0.1" dur="4.5s" repeatCount="indefinite" begin="0.7s"/></circle>
    <circle cx="650" cy="18" r="1.5" fill="#1f6feb"><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite" begin="0.2s"/></circle>
    <circle cx="750" cy="30" r="1" fill="#58a6ff"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="2.8s" repeatCount="indefinite" begin="0.9s"/></circle>
    <circle cx="820" cy="45" r="1.5" fill="#1f6feb"><animate attributeName="opacity" values="0.1;0.7;0.1" dur="3.2s" repeatCount="indefinite" begin="0.4s"/></circle>
    <circle cx="80" cy="190" r="1" fill="#58a6ff"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="2.5s" repeatCount="indefinite" begin="1.5s"/></circle>
    <circle cx="200" cy="200" r="1.5" fill="#1f6feb"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.8s" repeatCount="indefinite" begin="0.6s"/></circle>
    <circle cx="400" cy="195" r="1" fill="#58a6ff"><animate attributeName="opacity" values="0.1;0.6;0.1" dur="2.2s" repeatCount="indefinite" begin="1.1s"/></circle>
    <circle cx="600" cy="205" r="1.5" fill="#1f6feb"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="4s" repeatCount="indefinite" begin="0.8s"/></circle>
    <circle cx="780" cy="185" r="1" fill="#58a6ff"><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite" begin="0.1s"/></circle>
  </g>

  <!-- Código cayendo - columna izquierda -->
  <g font-family="'Courier New', monospace" font-size="11" fill="#1f6feb" opacity="0.5">
    <text x="28" y="0"><animate attributeName="y" values="-10;230" dur="4s" repeatCount="indefinite" begin="0s"/>const</text>
    <text x="28" y="0"><animate attributeName="y" values="-10;230" dur="4s" repeatCount="indefinite" begin="1.3s"/>= {}</text>
    <text x="28" y="0"><animate attributeName="opacity" values="0;0.8;0" dur="4s" repeatCount="indefinite" begin="2.6s">0x3F</text>
  </g>

  <!-- Código cayendo - columna derecha -->
  <g font-family="'Courier New', monospace" font-size="11" fill="#58a6ff" opacity="0.4">
    <text x="800" y="0"><animate attributeName="y" values="-10;230" dur="5s" repeatCount="indefinite" begin="0.5s"/>tsx</text>
    <text x="800" y="0"><animate attributeName="y" values="-10;230" dur="5s" repeatCount="indefinite" begin="2s"/>[]</text>
    <text x="800" y="0"><animate attributeName="y" values="-10;230" dur="5s" repeatCount="indefinite" begin="3.5s">=></text>
  </g>

  <!-- Líneas decorativas animadas -->
  <rect x="0" y="110" width="860" height="1" fill="url(#line1)" opacity="0.4">
    <animate attributeName="opacity" values="0.1;0.6;0.1" dur="3s" repeatCount="indefinite"/>
  </rect>
  <rect x="0" y="108" width="860" height="1" fill="url(#line2)" opacity="0.25">
    <animate attributeName="opacity" values="0.05;0.4;0.05" dur="3s" repeatCount="indefinite" begin="0.3s"/>
  </rect>

  <!-- Nombre principal con efecto glow -->
  <text x="430" y="95" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="52" font-weight="700" fill="#ffffff" filter="url(#glow2)" opacity="0.15">Estiven Rivas</text>
  <text x="430" y="95" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="52" font-weight="700" fill="url(#line1)">
    <animate attributeName="opacity" values="0;1" dur="1s" fill="freeze"/>
    Estiven Rivas
  </text>

  <!-- Línea decorativa bajo el nombre -->
  <line x1="230" y1="105" x2="630" y2="105" stroke="#1f6feb" stroke-width="1" opacity="0.5">
    <animate attributeName="x1" values="430;230" dur="1.2s" fill="freeze"/>
    <animate attributeName="x2" values="430;630" dur="1.2s" fill="freeze"/>
  </line>

  <!-- Subtítulo animado -->
  <text x="430" y="140" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="18" fill="#58a6ff" filter="url(#glow)">
    <animate attributeName="opacity" values="0;1" dur="1.5s" begin="0.8s" fill="freeze"/>
    ⚡ Full Stack Developer
  </text>

  <!-- Tags de tecnología animadas -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="1s" begin="1.5s" fill="freeze"/>

    <!-- React -->
    <rect x="175" y="160" width="70" height="26" rx="13" fill="#1f6feb" opacity="0.2"/>
    <rect x="175" y="160" width="70" height="26" rx="13" fill="none" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>
    <text x="210" y="177" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" fill="#58a6ff">React</text>

    <!-- Next.js -->
    <rect x="258" y="160" width="68" height="26" rx="13" fill="#ffffff" opacity="0.05"/>
    <rect x="258" y="160" width="68" height="26" rx="13" fill="none" stroke="#ffffff" stroke-width="1" opacity="0.3"/>
    <text x="292" y="177" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" fill="#ffffff">Next.js</text>

    <!-- TypeScript -->
    <rect x="339" y="160" width="88" height="26" rx="13" fill="#007acc" opacity="0.2"/>
    <rect x="339" y="160" width="88" height="26" rx="13" fill="none" stroke="#007acc" stroke-width="1" opacity="0.6"/>
    <text x="383" y="177" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" fill="#61b6f0">TypeScript</text>

    <!-- Node.js -->
    <rect x="440" y="160" width="74" height="26" rx="13" fill="#339933" opacity="0.2"/>
    <rect x="440" y="160" width="74" height="26" rx="13" fill="none" stroke="#339933" stroke-width="1" opacity="0.6"/>
    <text x="477" y="177" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" fill="#6bcb6b">Node.js</text>

    <!-- Colombia -->
    <rect x="527" y="160" width="86" height="26" rx="13" fill="#FFD700" opacity="0.1"/>
    <rect x="527" y="160" width="86" height="26" rx="13" fill="none" stroke="#FFD700" stroke-width="1" opacity="0.4"/>
    <text x="570" y="177" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" fill="#FFD700">🇨🇴 Colombia</text>
  </g>

  <!-- Punto de luz animado - orb superior izquierda -->
  <circle cx="100" cy="60" r="40" fill="#1f6feb" opacity="0.04">
    <animate attributeName="r" values="35;50;35" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.03;0.07;0.03" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- Punto de luz animado - orb superior derecha -->
  <circle cx="760" cy="80" r="50" fill="#58a6ff" opacity="0.03">
    <animate attributeName="r" values="45;60;45" dur="5s" repeatCount="indefinite" begin="1s"/>
    <animate attributeName="opacity" values="0.02;0.06;0.02" dur="5s" repeatCount="indefinite" begin="1s"/>
  </circle>

  <!-- Borde exterior elegante -->
  <rect x="1" y="1" width="858" height="218" fill="none" stroke="#1f6feb" stroke-width="1" rx="12" opacity="0.3"/>
  <rect x="3" y="3" width="854" height="214" fill="none" stroke="#58a6ff" stroke-width="0.5" rx="11" opacity="0.1"/>
</svg>

</div>

---

<!-- Typing animation via servicio confiable -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Construyendo+el+futuro+una+l%C3%ADnea+a+la+vez+%F0%9F%9A%80;React+%7C+Next.js+%7C+TypeScript+%7C+Node.js;Desarrollador+Full+Stack+%7C+Colombia+%F0%9F%87%A8%F0%9F%87%B4;Clean+code+%2B+buena+arquitectura+%3D+%E2%9D%A4%EF%B8%8F)](https://git.io/typing-svg)

</div>

---

## ⚡ Sobre mí

<img align="right" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="260" alt="coding"/>

Desarrollador Full Stack apasionado por construir aplicaciones web de alto rendimiento. Trabajo en toda la pila — desde interfaces responsivas hasta arquitecturas de backend escalables.

- 🔭 Trabajando en **proyectos full stack con Next.js y TypeScript**
- 🌱 Explorando patrones en **arquitectura React y diseño de APIs**
- ⚡ Me obsesiona el **código limpio y la buena arquitectura**
- 💬 Pregúntame sobre **JavaScript, TypeScript, React, Next.js**
- 🎯 Meta: **contribuir a proyectos open source**
- 📍 **Medellín, Colombia 🇨🇴**

<br clear="right"/>

---

## 🛠️ Stack Tecnológico

<div align="center">

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend y Herramientas**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 📊 Estadísticas de GitHub

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=estiwar3883&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&locale=es&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9" />
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=estiwar3883&layout=compact&theme=github_dark&hide_border=true&langs_count=6&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" />

</div>

<div align="center">

![Streak](https://streak-stats.demolab.com?user=estiwar3883&theme=github-dark-blue&hide_border=true&locale=es&background=0D1117&stroke=1F6FEB&ring=58A6FF&fire=FF7B54&currStreakLabel=58A6FF&sideLabels=58A6FF&dates=6B7280)

</div>

---

## 🚀 Proyectos Destacados

<div align="center">

[![ecommerce-lite](https://github-readme-stats.vercel.app/api/pin/?username=estiwar3883&repo=ecommerce-lite&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9)](https://github.com/estiwar3883/ecommerce-lite)
[![pagina-wed](https://github-readme-stats.vercel.app/api/pin/?username=estiwar3883&repo=pagina-wed&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9)](https://github.com/estiwar3883/pagina-wed)

</div>

---

<!-- FOOTER SVG animado propio -->
<div align="center">

<svg width="100%" viewBox="0 0 860 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footer-bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0f1923"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
  </defs>
  <rect width="860" height="80" fill="url(#footer-bg)" rx="8"/>
  <rect x="1" y="1" width="858" height="78" fill="none" stroke="#1f6feb" stroke-width="0.8" rx="8" opacity="0.3"/>

  <!-- Línea de código decorativa -->
  <text x="430" y="32" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#1f6feb" opacity="0.7">
    <animate attributeName="opacity" values="0.4;0.9;0.4" dur="3s" repeatCount="indefinite"/>
    // "Primero resuelve el problema. Luego escribe el código."
  </text>

  <text x="430" y="58" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" fill="#58a6ff" opacity="0.6">
    ⭐ Si te gusta mi trabajo, dale estrella a mis repos ⭐
  </text>
</svg>

</div>
