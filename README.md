
### 🌀 Visitors
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=zhanshuo-art&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

<div align="center">
  <svg width="300" height="300" viewBox="0 0 300 300" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <radialGradient id="chakra" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#00ffff" stop-opacity="1"/>
        <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
      </radialGradient>
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur in="SourceGraphic" stdDeviation="3" result="blur"/>
        <feMerge>
          <feMergeNo
    <!-- 查克拉背景波动 -->
    <circle cx="150" cy="150" r="120" fill="url(#chakra)" opacity="0.3">
      <animate attributeName="r" values="120;140;120" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0.6;0.3" dur="2s" repeatCount="indefinite"/>
    </circle>

    <!-- 写轮眼外圈 -->
    <g transform="translate(150,150)" filter="url(#glow)">
      <circle r="100" fill="none" stroke="#ff0000" stroke-width="4"/>
      <circle r="80" fill="none" stroke="#ff0000" stroke-width="2"/>
      <circle r="60" fill="none" stroke="#ff0000" stroke-width="2"/>
      
      <!-- 写轮眼勾玉 -->
      <g id="tomoe">
        <ellipse cx="0" cy="-70" rx="10" ry="20" fill="#ff0000" transform="rotate(0)"/>
        <ellipse cx="61" cy="35" rx="10" ry="20" fill="#ff0000" transform="rotate(120)"/>
        <ellipse cx="-61" cy="35" rx="10" ry="20" fill="#ff0000" transform="rotate(240)"/>
      </g>
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="10s" repeatCount="indefinite"/>
    </g>

    <!-- 忍者剪影 -->
    <image href="https://upload.wikimedia.org/wikipedia/commons/7/7a/Ninja-silhouette.svg" x="100" y="180" width="100" height="100" opacity="0.6">
      <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
    </image>
  </svg>
</div>

