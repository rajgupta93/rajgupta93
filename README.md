- 👋 Hi, I’m Raj Gupta
- 👀 I’m interested in android development
- 🌱 I’m currently learning dsa , android development .
- 💞️ I’m looking to collaborate on android project
- 📫 How to reach me rajg706891@gmail.com

<!---
rajgupta93/rajgupta93 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


      <svg
        width="495"
        height="195"
        viewBox="0 0 495 195"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #333;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    .rank-text {
      font: 800 24px 'Segoe UI', Ubuntu, Sans-Serif; fill: #333; 
      animation: scaleInAnimation 0.3s ease-in-out forwards;
    }
    
    .bold { font-weight: 700 }
    .icon {
      fill: #4c71f2;
      display: none;
    }
    
    .rank-circle-rim {
      stroke: #2f80ed;
      fill: none;
      stroke-width: 6;
      opacity: 0.2;
    }
    .rank-circle {
      stroke: #2f80ed;
      stroke-dasharray: 250;
      fill: none;
      stroke-width: 6;
      stroke-linecap: round;
      opacity: 0.8;
      transform-origin: -10px 8px;
      transform: rotate(-90deg);
      animation: rankAnimation 1s forwards ease-in-out;
    }
    
    @keyframes rankAnimation {
      from {
        stroke-dashoffset: 251.32741228718345;
      }
      to {
        stroke-dashoffset: 127.80197630685899;
      }
    }
  
  

          
    /* Animations */
    @keyframes scaleInAnimation {
      from {
        transform: translate(-5px, 5px) scale(0);
      }
      to {
        transform: translate(-5px, 5px) scale(1);
      }
    }
    @keyframes fadeInAnimation {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
  
          
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="494"
          fill="#fffefe"
          stroke-opacity="1"
        />

        
      <g
        data-testid="card-title"
        transform="translate(25, 35)"
      >
        <g transform="translate(0, 0)">
      <text
        x="0"
        y="0"
        class="header"
        data-testid="header"
      >Raj gupta's GitHub Stats</text>
    </g>
      </g>
    

        <g
          data-testid="main-card-body"
          transform="translate(0, 55)"
        >
          
    <g data-testid="rank-circle" 
          transform="translate(400, 47.5)">
        <circle class="rank-circle-rim" cx="-10" cy="8" r="40" />
        <circle class="rank-circle" cx="-10" cy="8" r="40" />
        <g class="rank-text">
          <text
            x="0"
            y="0"
            alignment-baseline="central"
            dominant-baseline="central"
            text-anchor="middle"
          >
            A+
          </text>
        </g>
      </g>

    <svg x="0" y="0">
      <g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms" transform="translate(25, 0)">
      
      <text class="stat bold"  y="12.5">Total Stars:</text>
      <text 
        class="stat" 
        x="170" 
        y="12.5" 
        data-testid="stars"
      >2</text>
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms" transform="translate(25, 0)">
      
      <text class="stat bold"  y="12.5">Total Commits (2021):</text>
      <text 
        class="stat" 
        x="170" 
        y="12.5" 
        data-testid="commits"
      >41</text>
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms" transform="translate(25, 0)">
      
      <text class="stat bold"  y="12.5">Total PRs:</text>
      <text 
        class="stat" 
        x="170" 
        y="12.5" 
        data-testid="prs"
      >4</text>
    </g>
  </g><g transform="translate(0, 75)">
    <g class="stagger" style="animation-delay: 900ms" transform="translate(25, 0)">
      
      <text class="stat bold"  y="12.5">Total Issues:</text>
      <text 
        class="stat" 
        x="170" 
        y="12.5" 
        data-testid="issues"
      >0</text>
    </g>
  </g><g transform="translate(0, 100)">
    <g class="stagger" style="animation-delay: 1050ms" transform="translate(25, 0)">
      
      <text class="stat bold"  y="12.5">Contributed to:</text>
      <text 
        class="stat" 
        x="170" 
        y="12.5" 
        data-testid="contribs"
      >4</text>
    </g>
  </g>
    </svg> 
  
        </g>
      </svg>
    
