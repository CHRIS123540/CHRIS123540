<!-- 使用div包裹以提高布局的灵活性和可控性 -->
<div style="position: relative;">

  <!-- 优化背景图展示 -->
  <img src="./assets/2.jpg" alt="Background Image" style="width: 200px; float: right; clear: both;">
  <img src="./assets/3.jpg" alt="Background Image" style="width: 200px; float: right; margin-top: 10px;">

</div>

<!-- 清除浮动，确保后续内容正确排版 -->
<br clear="all"/>

<!-- 使用更语义化的标签对内容进行分区 -->
<section>
  <h2 align="center">🎉 About Me</h2>

  <!-- 将Markdown内容放入markdown容器中，如果环境支持，可以通过样式或脚本转换 -->
  <div class="markdown">
    - 👋 Hi, I’m Chris  
    - 👀 I’m interested in HPC, i.e., CUDA and network i.e. DPDK & DOCA  
    - 🔭 I’m currently working on [Repath](https://github.com/CHRIS123540/Repath).  
    - 🏋️ I'm passionate about fitness, and it pays off.  
    - 👨‍💻 I'm passionate about coding and have been developing my skill.  
    - ⛺️ I have a private site: [Lingxiang Hu](https://chris123540.github.io/test/), you're welcome to come!  
    - 📨 My email address is `735514368@qq.com`. Welcome to contact me 👏🏻.  
  </div>
</section>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/github-snake.svg" />
  <img width="100%" alt="github-snake" src="./assets/github-snake.svg" />
</picture>
