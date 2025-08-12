<div align="center">

# ⛵ saanna225 ⛵

<br>

<!-- Ocean Scene -->
<svg width="800" height="300" viewBox="0 0 800 300" xmlns="http://www.w3.org/2000/svg">
  <!-- Ocean Background -->
  <defs>
    <linearGradient id="oceanGradient" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#87CEEB;stop-opacity:1" />
      <stop offset="30%" style="stop-color:#4682B4;stop-opacity:1" />
      <stop offset="70%" style="stop-color:#2E8B57;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#1e3a5f;stop-opacity:1" />
    </linearGradient>
    <!-- Wave Pattern -->
    <pattern id="waves" x="0" y="0" width="100" height="20" patternUnits="userSpaceOnUse">
      <path d="M0,10 Q25,0 50,10 T100,10 V20 H0 Z" fill="rgba(255,255,255,0.1)"/>
    </pattern>
  </defs>
  
  <!-- Ocean -->
  <rect width="800" height="300" fill="url(#oceanGradient)"/>
  <rect width="800" height="300" fill="url(#waves)"/>
  
  <!-- Animated Bubbles -->
  <circle cx="100" cy="250" r="8" fill="rgba(255,255,255,0.4)" opacity="0.7">
    <animate attributeName="cy" values="300;50;300" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="280" r="6" fill="rgba(255,255,255,0.5)" opacity="0.5">
    <animate attributeName="cy" values="300;30;300" dur="8s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="opacity" values="0;1;0" dur="8s" repeatCount="indefinite" begin="2s"/>
  </circle>
  <circle cx="600" cy="270" r="10" fill="rgba(255,255,255,0.3)" opacity="0.6">
    <animate attributeName="cy" values="300;40;300" dur="7s" repeatCount="indefinite" begin="4s"/>
    <animate attributeName="opacity" values="0;1;0" dur="7s" repeatCount="indefinite" begin="4s"/>
  </circle>
  <circle cx="700" cy="290" r="5" fill="rgba(255,255,255,0.6)" opacity="0.8">
    <animate attributeName="cy" values="300;20;300" dur="9s" repeatCount="indefinite" begin="1s"/>
    <animate attributeName="opacity" values="0;1;0" dur="9s" repeatCount="indefinite" begin="1s"/>
  </circle>
  
  <!-- Boat -->
  <g transform="translate(400,80)">
    <!-- Boat Hull -->
    <path d="M-80,40 Q0,55 80,40 L70,50 Q0,60 -70,50 Z" fill="#8B4513" stroke="#654321" stroke-width="2">
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="3s" repeatCount="indefinite"/>
    </path>
    <!-- Mast -->
    <line x1="0" y1="40" x2="0" y2="-20" stroke="#654321" stroke-width="3">
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="3s" repeatCount="indefinite"/>
    </line>
    <!-- Sail -->
    <path d="M5,-15 Q35,-5 5,35" fill="#F0F8FF" stroke="#87CEEB" stroke-width="2">
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="3s" repeatCount="indefinite"/>
    </path>
    <!-- Username on Sail -->
    <text x="15" y="10" font-family="Arial, sans-serif" font-size="12" font-weight="bold" fill="#2E8B57">
      saanna225
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="3s" repeatCount="indefinite"/>
    </text>
    <!-- Flag -->
    <path d="M0,-20 L25,-15 L0,-10 Z" fill="#FF6B6B">
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-5; 0,0" dur="3s" repeatCount="indefinite"/>
    </path>
  </g>
  
  <!-- Treasure Chest -->
  <g transform="translate(680,220)">
    <!-- Chest Base -->
    <rect x="-25" y="0" width="50" height="20" fill="#8B4513" stroke="#654321" stroke-width="2" rx="3"/>
    <!-- Chest Lid -->
    <path d="M-25,0 Q0,-10 25,0" fill="#A0522D" stroke="#654321" stroke-width="2"/>
    <!-- Lock -->
    <circle cx="0" cy="10" r="3" fill="#FFD700" stroke="#FFA500" stroke-width="1"/>
    <!-- Sparkles -->
    <text x="-15" y="-5" font-size="6" fill="#FFD700">✨</text>
    <text x="10" y="-8" font-size="5" fill="#FFD700">✨</text>
  </g>
  
  <!-- Seaweed -->
  <g transform="translate(50,200)">
    <path d="M0,0 Q-10,20 0,40 Q10,60 0,80" stroke="#228B22" stroke-width="3" fill="none" opacity="0.7">
      <animate attributeName="d" values="M0,0 Q-10,20 0,40 Q10,60 0,80; M0,0 Q10,20 0,40 Q-10,60 0,80; M0,0 Q-10,20 0,40 Q10,60 0,80" dur="4s" repeatCount="indefinite"/>
    </path>
  </g>
  <g transform="translate(750,180)">
    <path d="M0,0 Q8,25 0,50 Q-8,75 0,100" stroke="#32CD32" stroke-width="2" fill="none" opacity="0.6">
      <animate attributeName="d" values="M0,0 Q8,25 0,50 Q-8,75 0,100; M0,0 Q-8,25 0,50 Q8,75 0,100; M0,0 Q8,25 0,50 Q-8,75 0,100" dur="5s" repeatCount="indefinite"/>
    </path>
  </g>
</svg>

<br><br>

## 🐚 My Project Treasures

<p align="center">
  
  <a href="https://github.com/saanna225/project1">
    <img src="https://github.com/user-attachments/assets/clam-purple.svg" alt="Kaggle Competition" width="80" height="60" title="🟣 Kaggle Competition"/>
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/saanna225/project2">
    <img src="https://github.com/user-attachments/assets/clam-pink.svg" alt="Project 2" width="80" height="60" title="🌸 Project 2"/>
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/saanna225/project3">
    <img src="https://github.com/user-attachments/assets/clam-green.svg" alt="Project 3" width="80" height="60" title="💚 Project 3"/>
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/saanna225/project4">
    <img src="https://github.com/user-attachments/assets/clam-blue.svg" alt="Project 4" width="80" height="60" title="💙 Project 4"/>
  </a>
  
</p>

<!-- Custom Clam SVGs as fallback -->
<p align="center">
  
<svg width="80" height="60" viewBox="0 0 80 60">
  <path d="M40,50 Q20,35 25,20 Q30,15 40,20 Q50,15 55,20 Q60,35 40,50" fill="#DDA0DD" stroke="#9370DB" stroke-width="2"/>
  <path d="M40,20 Q30,12 25,20 Q35,25 40,20 Q45,25 55,20 Q50,12 40,20" fill="#E6E6FA" stroke="#9370DB" stroke-width="2"/>
  <circle cx="40" cy="32" r="4" fill="#F8F8FF" stroke="#E0E0E0" stroke-width="1"/>
  <circle cx="38" cy="30" r="1.5" fill="#FFFFFF"/>
</svg>
&nbsp;&nbsp;&nbsp;&nbsp;
<svg width="80" height="60" viewBox="0 0 80 60">
  <path d="M40,50 Q20,35 25,20 Q30,15 40,20 Q50,15 55,20 Q60,35 40,50" fill="#FFB6C1" stroke="#FF69B4" stroke-width="2"/>
  <path d="M40,20 Q30,12 25,20 Q35,25 40,20 Q45,25 55,20 Q50,12 40,20" fill="#FFC0CB" stroke="#FF69B4" stroke-width="2"/>
  <circle cx="40" cy="32" r="4" fill="#FF1493" stroke="#DC143C" stroke-width="1"/>
  <circle cx="38" cy="30" r="1.5" fill="#FFFFFF"/>
</svg>
&nbsp;&nbsp;&nbsp;&nbsp;
<svg width="80" height="60" viewBox="0 0 80 60">
  <path d="M40,50 Q20,35 25,20 Q30,15 40,20 Q50,15 55,20 Q60,35 40,50" fill="#98FB98" stroke="#32CD32" stroke-width="2"/>
  <path d="M40,20 Q30,12 25,20 Q35,25 40,20 Q45,25 55,20 Q50,12 40,20" fill="#90EE90" stroke="#32CD32" stroke-width="2"/>
  <circle cx="40" cy="32" r="4" fill="#00FF7F" stroke="#00FF00" stroke-width="1"/>
  <circle cx="38" cy="30" r="1.5" fill="#FFFFFF"/>
</svg>
&nbsp;&nbsp;&nbsp;&nbsp;
<svg width="80" height="60" viewBox="0 0 80 60">
  <path d="M40,50 Q20,35 25,20 Q30,15 40,20 Q50,15 55,20 Q60,35 40,50" fill="#87CEEB" stroke="#4169E1" stroke-width="2"/>
  <path d="M40,20 Q30,12 25,20 Q35,25 40,20 Q45,25 55,20 Q50,12 40,20" fill="#B0E0E6" stroke="#4169E1" stroke-width="2"/>
  <circle cx="40" cy="32" r="4" fill="#1E90FF" stroke="#0000FF" stroke-width="1"/>
  <circle cx="38" cy="30" r="1.5" fill="#FFFFFF"/>
</svg>

</p>

<br>

## ⚓ About Me

🌊 **Sailing through the vast ocean of code, discovering new technologies like hidden treasures**

🐚 **Each repository is a precious pearl I've cultivated with care**

⛵ **Currently navigating:** Data Science & Machine Learning

🗺️ **Charting course towards:** Becoming my own boss in tech

📫 **Send a message in a bottle:** sahanadiwakar12@gmail.com

<br>

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=saanna225&show_icons=true&theme=tokyonight&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=1f6feb" alt="GitHub Stats" />
  
  <br><br>
  
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=saanna225&theme=tokyonight&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=c9d1d9" alt="GitHub Streak" />
</div>

<br>

<div align="center">
  
  **⚡ Languages & Tools ⚡**
  
  ![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
  ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
  ![Scikit Learn](https://img.shields.io/badge/-Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
  
</div>

<br>

<div align="center">
  
  **🏆 GitHub Trophies 🏆**
  
  [![trophy](https://github-profile-trophy.vercel.app/?username=saanna225&theme=onestar&no-frame=true&column=6&margin-w=15&margin-h=15)](https://github.com/ryo-ma/github-profile-trophy)
  
</div>

<br>

---

<p align="center">
  <i>🌊 "Water water everywhere not a drop to drink " 🌊</i>
</p>

</div>
