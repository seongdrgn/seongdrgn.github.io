---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.section-sep { border: none; border-top: 1px solid #ccc; margin: 48px 0; }
.pub { display:flex; align-items:flex-start; gap:20px; margin-bottom:32px; flex-wrap:wrap; }
.pub-thumb { width:300px; flex-shrink:0; margin-top:6px; }
.pub-thumb img { width:100%; border-radius:4px; }
.pub-title { color:#003566; font-weight:700; }
.entry { display:grid; grid-template-columns:1fr 150px; gap:2px 22px; align-items:start; padding:12px 0; border-bottom:1px solid #f0f0f0; }
.entry:last-of-type { border-bottom:none; }
.entry-date { white-space:nowrap; color:#666; font-size:0.85em; text-align:right; }
.note { color:#777; font-size:0.85em; }
.links { margin-top:8px; }
.links a { display:inline-block; padding:3px 12px; margin:4px 6px 0 0; border-radius:5px; background:#003566; color:#fff; font-size:0.82em; font-weight:600; text-decoration:none; border:1px solid #003566; }
.links a:hover { background:#0a4f8a; border-color:#0a4f8a; }
.tag { display:inline-block; padding:1px 9px; border-radius:4px; background:#ffe2a8; color:#8a5300; font-size:0.78em; font-weight:700; letter-spacing:0.2px; }
@media (max-width: 600px) {
  .pub-thumb { width:100%; }
  .entry { grid-template-columns:1fr; gap:4px; }
  .entry-date { text-align:left; }
}
</style>

I am a Ph.D. candidate in Mechanical Engineering at Dongguk University, Korea, where I also completed my M.S. degree. My research is supervised by Professor [Soo-Chul Lim](http://irobot.dgu.edu/).

My research interests include **reinforcement learning and deep learning for robotics**, with a focus on deploying various robotic tasks in real-world environments.

<hr class="section-sep">

## Publications

<div class="pub">
  <div class="pub-thumb">
    <img src="files/pixel2catch.gif" alt="Pixel2Catch">
  </div>
  <div>
    <span class="pub-title">Pixel2Catch: Multi-Agent Sim-to-Real Transfer for Agile Manipulation with a Single RGB Camera</span><br>
    <b>Seongyong Kim</b>, Junhyeon Cho, Kang-Won Lee, Soo-Chul Lim<br>
    <i>IEEE Robotics and Automation Letters (RA-L), 2026 (Accepted)</i>
    <div class="links">
      <a href="https://seongdrgn.github.io/pixel2catch/" target="_blank">Project Page</a>
      <a href="https://www.youtube.com/watch?v=kV10T-2zh5w" target="_blank">Video</a>
      <a href="https://github.com/seongdrgn/pixel2catch-github" target="_blank">Code</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb">
    <img src="files/progressive_policy_learning.gif" alt="Progressive Policy Learning">
  </div>
  <div>
    <span class="pub-title">Progressive Policy Learning: A Hierarchical Framework for Dexterous Bimanual Manipulation</span><br>
    Kang-Won Lee, Jung-Woo Lee, <b>Seongyong Kim</b>, Soo-Chul Lim<br>
    <i>Mathematics 2025, 13(22), 3585</i>
    <div class="links">
      <a href="https://www.mdpi.com/2227-7390/13/22/3585" target="_blank">Paper</a>
      <a href="https://www.youtube.com/watch?v=PXLsaaZMp6w" target="_blank">Video</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb">
    <img src="files/video_prediction_result.gif" alt="Scene Prediction">
  </div>
  <div>
    <span class="pub-title">Prediction of Delay-Free Scene for Quadruped Robot Teleoperation: Integrating Delayed Data with User Commands</span><br>
    Seunghyeon Ha*, <b>Seongyong Kim*</b>, Soo-Chul Lim<br>
    <i>IEEE Robotics and Automation Letters, vol. 10, no. 3, pp. 2846–2853, March 2025</i><br>
    <i>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2025)</i> <span class="tag">Oral &amp; Poster Presentation</span>
    <div class="links">
      <a href="https://ieeexplore.ieee.org/document/10857415" target="_blank">Paper</a>
      <a href="https://seongdrgn.github.io/scene-prediction-quadruped/" target="_blank">Project Page</a>
      <a href="https://www.youtube.com/watch?v=wL9UEJnq53s" target="_blank">Video</a>
      <a href="files/IROS2025_Poster.pdf" target="_blank">Poster</a>
    </div>
    <span class="note">* Equal contribution</span>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb">
    <img src="files/array_tactile.gif" alt="Array Tactile">
  </div>
  <div>
    <span class="pub-title">Effects of Sensing Tactile Arrays, Shear Force, and Proprioception of Robot on Texture Recognition</span><br>
    Jung-Hwan Yang, <b>Seongyong Kim</b>, Soo-Chul Lim<br>
    <i>Sensors 23, no. 6: 3201</i>
    <div class="links">
      <a href="https://www.mdpi.com/1424-8220/23/6/3201" target="_blank">Paper</a>
      <a href="https://www.youtube.com/watch?v=l--EEY5fy4g" target="_blank">Video</a>
    </div>
  </div>
</div>

<hr class="section-sep">

## Projects

<div class="entry">
  <div>Development of Intelligent Autonomous Manipulation Technology for Humanoids with Reduced Dependency on Real-World Data</div>
  <div class="entry-date">Jul 2025 – Present</div>
</div>

<div class="entry">
  <div>Robot Motion Generation AI based on Multimodal Vision/Tactile Information Driven by Language Model</div>
  <div class="entry-date">Mar 2025 – Present</div>
</div>

<div class="entry">
  <div>
    Collecting Large-scale Robot Manipulation Data in Physical Environment
    <div class="links">
      <a href="https://github.com/seongdrgn/Large-Scale-Robotic-Manipulation-Data-Collection" target="_blank">GitHub</a>
      <a href="https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=71825" target="_blank">Dataset</a>
    </div>
  </div>
  <div class="entry-date">Aug 2024 – Dec 2024</div>
</div>

<div class="entry">
  <div>Development of a High-performance Multimodal Electronic Skin Sensor of Hybrid-type and A Scalable Module for Robot Manipulation</div>
  <div class="entry-date">2021 – 2023</div>
</div>

<hr class="section-sep">

## Awards

<div class="entry">
  <div>Best Paper Award, <i>2025 Summer Conference of BK21FOUR AIMS Center</i></div>
  <div class="entry-date">2025</div>
</div>

<hr class="section-sep">

## Presentations

<div class="entry">
  <div>
    Prediction of Delay-Free Scene for Quadruped Robot Teleoperation: Integrating Delayed Data With User Commands,
    <i>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</i>
    <div class="links">
      <a href="files/IROS2025_Poster.pdf" target="_blank">Poster</a>
    </div>
  </div>
  <div class="entry-date">2025</div>
</div>

<div class="entry">
  <div>Multi-agent Reinforcement Learning for Catching Thrown Object using Pixel-wise Features, <i>Workshop in Robot Learning (KROS)</i></div>
  <div class="entry-date">2025</div>
</div>

<hr class="section-sep">

## Work Experience

<div class="entry">
  <div>Teaching Assistant for Introduction to Intelligent Robotics (Dongguk Univ., MEC4100)</div>
  <div class="entry-date">Mar – Jun 2025<br>Mar – Jun 2024</div>
</div>

<div class="entry">
  <div>Teaching Assistant for Dynamics (Dongguk Univ., MEC2012)</div>
  <div class="entry-date">Sep – Dec 2024<br>Sep – Dec 2022</div>
</div>
