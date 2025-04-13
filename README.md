<div align="center">
  <style>
    /* Glitch effect style */
    .glitch {
      font-family: 'Sacramento', cursive;
      font-size: 50px;
      color: #9D65C9;
      position: relative;
      display: inline-block;
      animation: glitch 1s infinite;
    }

    .glitch:before, .glitch:after {
      content: "skimatt";
      position: absolute;
      top: 0;
      left: 0;
      color: #9D65C9;
      overflow: hidden;
      clip: rect(0, 900px, 0, 0);
      z-index: -1;
    }

    .glitch:before {
      animation: glitch-before 1s infinite;
      left: 2px;
      text-shadow: -1px 0 red, 1px 0 blue;
    }

    .glitch:after {
      animation: glitch-after 1s infinite;
      left: -2px;
      text-shadow: 1px 0 red, -1px 0 blue;
    }

    @keyframes glitch {
      0% { transform: translate(0); }
      20% { transform: translate(-2px, -2px); }
      40% { transform: translate(-3px, 0); }
      60% { transform: translate(3px, 2px); }
      80% { transform: translate(2px, -1px); }
      100% { transform: translate(0); }
    }

    @keyframes glitch-before {
      0% { clip: rect(0, 900px, 0, 0); }
      25% { clip: rect(0, 900px, 0, 0); }
      50% { clip: rect(0, 900px, 0, 0); }
      75% { clip: rect(0, 900px, 0, 0); }
      100% { clip: rect(0, 900px, 0, 0); }
    }

    @keyframes glitch-after {
      0% { clip: rect(0, 900px, 0, 0); }
      25% { clip: rect(0, 900px, 0, 0); }
      50% { clip: rect(0, 900px, 0, 0); }
      75% { clip: rect(0, 900px, 0, 0); }
      100% { clip: rect(0, 900px, 0, 0); }
    }
  </style>

  <!-- Glitch effect text -->
  <span class="glitch">skimatt</span>
</div>


  <!-- Forest Landscape GIF -->
  <img src="https://i.pinimg.com/originals/05/26/fc/0526fc32bae551832ca57149d92c5dd0.gif" alt="Forest Landscape" width="800"/>

  <!-- Garden Tools Badge -->
  <a href="https://github.com/skimatt">
    <img src="https://skillicons.dev/icons?i=html,css,js,python,php,react,nodejs,mysql,git,vscode&theme=dark" alt="Garden Tools" />
  </a>

  <!-- GitHub Streak Stats -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=skimatt&theme=material-palenight&hide_border=true&background=1E1033&stroke=9D65C9&fire=B288E0&currStreakNum=AA7ED3&ring=8A4FBD&currStreakLabel=AA7ED3&sideNums=AA7ED3&sideLabels=8A4FBD" alt="GitHub Streak" height="180em" />

  <!-- GitHub Stats and Top Languages -->
  <table>
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=skimatt&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1E1033&title_color=AA7ED3&text_color=B288E0&icon_color=8A4FBD" alt="GitHub Stats"/>
      </td>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=skimatt&layout=compact&theme=tokyonight&hide_border=true&bg_color=1E1033&title_color=AA7ED3&text_color=B288E0" alt="Top Languages"/>
      </td>
    </tr>
  </table>

  <!-- GitHub Trophies displayed horizontally -->
  <div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 15px;">
    <img src="https://github-profile-trophy.vercel.app/?username=skimatt&theme=discord&no-frame=true&margin-w=15&margin-h=15&column=8" alt="GitHub Trophies" />

  </div>

  <!-- Instagram and Portfolio Badges -->
  <a href="https://instagram.com/skimatt_">
    <img src="https://img.shields.io/badge/Instagram-1E1033?style=for-the-badge&logo=instagram&logoColor=AA7ED3" alt="Instagram"/>
  </a>
  <a href="https://skimatt.github.io/RahmatMulia/">
    <img src="https://img.shields.io/badge/Portfolio-1E1033?style=for-the-badge&logo=google-chrome&logoColor=9D65C9" alt="Portfolio"/>
  </a>

  <!-- Profile Views Counter -->
  <img src="https://komarev.com/ghpvc/?username=skimatt&color=9D65C9&style=flat-square&base=1654" alt="Profile Views"/>

  <!-- Contribution Snake Animation -->
  <div>
    <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg" alt="Contribution Snake Animation" width="100%">
  </div>

  <!-- Quote -->
  <em>"Hello World!" — Skimatt</em>
</div>
