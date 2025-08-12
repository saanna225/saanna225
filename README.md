<div align="center">
<!-- Ocean Container -->
<div style="
  position: relative;
  width: 100%;
  height: 500px;
  background: linear-gradient(180deg, 
    #87CEEB 0%, 
    #4682B4 30%, 
    #2E8B57 70%, 
    #1e3a5f 100%);
  overflow: hidden;
  border-radius: 15px;
  margin: 20px 0;
">
  <!-- Animated Bubbles -->
  <div style="
    position: absolute;
    width: 100%;
    height: 100%;
    pointer-events: none;
  ">
    <!-- Bubble 1 -->
    <div style="
      position: absolute;
      width: 20px;
      height: 20px;
      background: rgba(255,255,255,0.3);
      border-radius: 50%;
      left: 10%;
      bottom: -20px;
      animation: float 6s infinite linear;
    "></div>
    <!-- Bubble 2 -->
    <div style="
      position: absolute;
      width: 15px;
      height: 15px;
      background: rgba(255,255,255,0.4);
      border-radius: 50%;
      left: 30%;
      bottom: -15px;
      animation: float 8s infinite linear 2s;
    "></div>
    <!-- Bubble 3 -->
    <div style="
      position: absolute;
      width: 25px;
      height: 25px;
      background: rgba(255,255,255,0.2);
      border-radius: 50%;
      left: 70%;
      bottom: -25px;
      animation: float 7s infinite linear 4s;
    "></div>
    <!-- Bubble 4 -->
    <div style="
      position: absolute;
      width: 12px;
      height: 12px;
      background: rgba(255,255,255,0.5);
      border-radius: 50%;
      left: 85%;
      bottom: -12px;
      animation: float 9s infinite linear 1s;
    "></div>
    <!-- Bubble 5 -->
    <div style="
      position: absolute;
      width: 18px;
      height: 18px;
      background: rgba(255,255,255,0.3);
      border-radius: 50%;
      left: 50%;
      bottom: -18px;
      animation: float 5s infinite linear 3s;
    "></div>
  </div>
  <!-- Boat with Username -->
  <div style="
    position: absolute;
    top: 50px;
    left: 50%;
    transform: translateX(-50%);
    animation: boat-bob 3s ease-in-out infinite;
  ">
    <svg width="200" height="120" viewBox="0 0 200 120">
      <!-- Boat Hull -->
      <path d="M20 80 Q100 95 180 80 L170 90 Q100 100 30 90 Z" 
            fill="#8B4513" stroke="#654321" stroke-width="2"/>
      <!-- Mast -->
      <line x1="100" y1="80" x2="100" y2="20" stroke="#654321" stroke-width="4"/>
      <!-- Sail -->
      <path d="M105 25 Q140 35 105 75" fill="#F0F8FF" stroke="#87CEEB" stroke-width="2"/>
      <!-- Username on Sail -->
      <text x="115" y="50" font-family="Arial, sans-serif" font-size="14" font-weight="bold" fill="#2E8B57">
        saanna225
      </text>
      <!-- Flag -->
      <path d="M100 20 L130 25 L100 30 Z" fill="#FF6B6B"/>
    </svg>
  </div>
  <!-- Treasure Chest (Contributions) -->
  <div style="
    position: absolute;
    bottom: 40px;
    right: 50px;
    cursor: pointer;
  ">
    <svg width="80" height="60" viewBox="0 0 80 60">
      <!-- Chest Base -->
      <rect x="10" y="30" width="60" height="25" fill="#8B4513" stroke="#654321" stroke-width="2" rx="3"/>
      <!-- Chest Lid -->
      <path d="M10 30 Q40 15 70 30" fill="#A0522D" stroke="#654321" stroke-width="2"/>
      <!-- Lock -->
      <circle cx="40" cy="42" r="4" fill="#FFD700" stroke="#FFA500" stroke-width="1"/>
      <!-- Sparkles -->
      <text x="25" y="25" font-size="8" fill="#FFD700">✨</text>
      <text x="50" y="20" font-size="6" fill="#FFD700">✨</text>
    </svg>
  </div>
</div>
<!-- CSS Animations -->
<style>
@keyframes float {
  0% {
    bottom: -30px;
    opacity: 0.7;
  }
  50% {
    opacity: 1;
  }
  100% {
    bottom: 500px;
    opacity: 0;
  }
}

@keyframes boat-bob {
  0%, 100% {
    transform: translateX(-50%) translateY(0px);
  }
  50% {
    transform: translateX(-50%) translateY(-8px);
  }
}

@keyframes wave {
  0%, 100% {
    transform: translateX(0);
  }
  50% {
    transform: translateX(20px);
  }
}
</style>
🐚 My Project Treasures
<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin: 30px 0;">
  <!-- Repository Clam 1 -->
  <a href="https://github.com/saanna225/repo759" style="text-decoration: none;">
    <div style="
      position: relative;
      cursor: pointer;
      transition: transform 0.3s ease;
    " onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'">
      <svg width="100" height="80" viewBox="0 0 100 80">
        <!-- Clam Shell Bottom -->
        <path d="M50 70 Q20 50 30 30 Q40 25 50 30 Q60 25 70 30 Q80 50 50 70" 
              fill="#DDA0DD" stroke="#9370DB" stroke-width="2"/>
        <!-- Clam Shell Top -->
        <path d="M50 30 Q35 20 30 30 Q40 35 50 30 Q60 35 70 30 Q65 20 50 30" 
              fill="#E6E6FA" stroke="#9370DB" stroke-width="2"/>
        <!-- Pearl -->
        <circle cx="50" cy="45" r="6" fill="#F8F8FF" stroke="#E0E0E0" stroke-width="1" opacity="0.9"/>
        <!-- Shine on pearl -->
        <circle cx="47" cy="42" r="2" fill="#FFFFFF" opacity="0.7"/>
      </svg>
      <div style="
        position: absolute;
        top: -25px;
        left: 50%;
        transform: translateX(-50%);
        background: rgba(0,0,0,0.8);
        color: white;
        padding: 5px 10px;
        border-radius: 5px;
        font-size: 12px;
        opacity: 0;
        transition: opacity 0.3s;
        pointer-events: none;
        white-space: nowrap;
      " class="tooltip">
        Project Name 1
      </div>
    </div>
  </a>
  <!-- Repository Clam 2 -->
  <a href="https://github.com/saanna225/projects" style="text-decoration: none;">
    <div style="
      position: relative;
      cursor: pointer;
      transition: transform 0.3s ease;
    " onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'">
      <svg width="100" height="80" viewBox="0 0 100 80">
        <path d="M50 70 Q20 50 30 30 Q40 25 50 30 Q60 25 70 30 Q80 50 50 70" 
              fill="#FFB6C1" stroke="#FF69B4" stroke-width="2"/>
        <path d="M50 30 Q35 20 30 30 Q40 35 50 30 Q60 35 70 30 Q65 20 50 30" 
              fill="#FFC0CB" stroke="#FF69B4" stroke-width="2"/>
        <circle cx="50" cy="45" r="6" fill="#FF1493" stroke="#DC143C" stroke-width="1" opacity="0.8"/>
        <circle cx="47" cy="42" r="2" fill="#FFFFFF" opacity="0.7"/>
      </svg>
      <div style="
        position: absolute;
        top: -25px;
        left: 50%;
        transform: translateX(-50%);
        background: rgba(0,0,0,0.8);
        color: white;
        padding: 5px 10px;
        border-radius: 5px;
        font-size: 12px;
        opacity: 0;
        transition: opacity 0.3s;
        pointer-events: none;
        white-space: nowrap;
      " class="tooltip">
        Project Name 2
      </div>
    </div>
  </a>
  <!-- Repository Clam 3 -->
  <a href="https://github.com/saanna225/profile" style="text-decoration: none;">
    <div style="
      position: relative;
      cursor: pointer;
      transition: transform 0.3s ease;
    " onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'">
      <svg width="100" height="80" viewBox="0 0 100 80">
        <path d="M50 70 Q20 50 30 30 Q40 25 50 30 Q60 25 70 30 Q80 50 50 70" 
              fill="#98FB98" stroke="#32CD32" stroke-width="2"/>
        <path d="M50 30 Q35 20 30 30 Q40 35 50 30 Q60 35 70 30 Q65 20 50 30" 
              fill="#90EE90" stroke="#32CD32" stroke-width="2"/>
        <circle cx="50" cy="45" r="6" fill="#00FF7F" stroke="#00FF00" stroke-width="1" opacity="0.8"/>
        <circle cx="47" cy="42" r="2" fill="#FFFFFF" opacity="0.7"/>
      </svg>
      <div style="
        position: absolute;
        top: -25px;
        left: 50%;
        transform: translateX(-50%);
        background: rgba(0,0,0,0.8);
        color: white;
        padding: 5px 10px;
        border-radius: 5px;
        font-size: 12px;
        opacity: 0;
        transition: opacity 0.3s;
        pointer-events: none;
        white-space: nowrap;
      " class="tooltip">
        Project Name 3
      </div>
    </div>
  </a>
  <!-- Repository Clam 4 -->
  <a href="https://github.com/saanna225/Kaggle_competition" style="text-decoration: none;">
    <div style="
      position: relative;
      cursor: pointer;
      transition: transform 0.3s ease;
    " onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'">
      <svg width="100" height="80" viewBox="0 0 100 80">
        <path d="M50 70 Q20 50 30 30 Q40 25 50 30 Q60 25 70 30 Q80 50 50 70" 
              fill="#87CEEB" stroke="#4169E1" stroke-width="2"/>
        <path d="M50 30 Q35 20 30 30 Q40 35 50 30 Q60 35 70 30 Q65 20 50 30" 
              fill="#B0E0E6" stroke="#4169E1" stroke-width="2"/>
        <circle cx="50" cy="45" r="6" fill="#1E90FF" stroke="#0000FF" stroke-width="1" opacity="0.8"/>
        <circle cx="47" cy="42" r="2" fill="#FFFFFF" opacity="0.7"/>
      </svg>
      <div style="
        position: absolute;
        top: -25px;
        left: 50%;
        transform: translateX(-50%);
        background: rgba(0,0,0,0.8);
        color: white;
        padding: 5px 10px;
        border-radius: 5px;
        font-size: 12px;
        opacity: 0;
        transition: opacity 0.3s;
        pointer-events: none;
        white-space: nowrap;
      " class="tooltip">
        Project Name 4
      </div>
    </div>
  </a>
</div>
⚓ About Me
🌊 Sailing through the vast ocean of code, discovering new technologies like hidden treasures
🐚 Each repository is a precious pearl I've cultivated with care
⛵ Currently navigating: Through many things , learning everyday !
🗺️ Charting course towards: Be my own Boss 
📫 Send a message in a bottle: sahanadiwakar12@gmail.com

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=saanna225&show_icons=true&theme=ocean_dark" alt="GitHub Stats" />
</div>
<script>
// Add hover effects for tooltips
document.addEventListener('DOMContentLoaded', function() {
  const clams = document.querySelectorAll('[onmouseover]');
  clams.forEach(clam => {
    const tooltip = clam.querySelector('.tooltip');
    clam.addEventListener('mouseenter', () => {
      if(tooltip) tooltip.style.opacity = '1';
    });
    clam.addEventListener('mouseleave', () => {
      if(tooltip) tooltip.style.opacity = '0';
    });
  });
});
</script>
</div>
