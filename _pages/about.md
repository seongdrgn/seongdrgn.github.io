<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<style>
  body {
    font-family: Arial, sans-serif;
    max-width: 860px;
    margin: 0 auto;
    padding: 30px 20px;
    font-size: 14px;
    color: #222;
    line-height: 1.6;
  }

  /* Section headings */
  h2 {
    font-size: 1.15em;
    font-weight: bold;
    border-bottom: 2px solid #ccc;
    padding-bottom: 4px;
    margin-top: 48px;
    margin-bottom: 16px;
  }

  hr { border: none; border-top: 1px solid #ccc; margin: 48px 0; }

  /* Generic left-content / right-date row */
  .entry {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin: 14px 0;
    gap: 24px;
  }
  .entry-left  { flex: 1; }
  .entry-right {
    white-space: nowrap;
    color: #555;
    font-size: 0.9em;
    min-width: 150px;
    text-align: right;
  }
  .entry-left a {
    margin-right: 6px;
    color: #1a0dab;
    text-decoration: none;
    font-size: 0.9em;
  }
  .entry-left a:hover { text-decoration: underline; }

  /* Publications */
  .pub {
    display: flex;
    align-items: flex-start;
    margin-bottom: 36px;
    gap: 20px;
  }
  .pub-img {
    width: 200px;
    flex-shrink: 0;
  }
  .pub-img img { width: 100%; border-radius: 4px; }
  .pub-body { flex: 1; }
  .pub-title {
    color: #003566;
    font-weight: bold;
  }
  .pub-body a {
    margin-right: 6px;
    color: #1a0dab;
    text-decoration: none;
    font-size: 0.9em;
  }
  .pub-body a:hover { text-decoration: underline; }
  .pub-venue { font-style: italic; color: #444; }
</style>
</head>
<body>

<!-- ── Intro ─────────────────────────────────────────── -->
<p>
  I am a Ph.D. candidate in Mechanical Engineering at Dongguk University, Korea, where I also completed my M.S. degree.
  My research is supervised by Professor <a href="http://irobot.dgu.edu/" target="_blank">Soo-Chul Lim</a>.
</p>
<p>
  My research interests include <strong>reinforcement learning and deep learning for robotics</strong>,
  with a focus on deploying various robotic tasks in real-world environments.
</p>

<hr>

<!-- ── Publications ───────────────────────────────────── -->
<h2>Publications</h2>

<div class="pub">
  <div class="pub-img">
    <img src="files/progressive_policy_learning.gif" alt="Progressive Policy Learning">
  </div>
  <div class="pub-body">
    <div class="pub-title">Progressive Policy Learning: A Hierarchical Framework for Dexterous Bimanual Manipulation</div>
    Kang-Won Lee*, Jung-Woo Lee, <strong>Seongyong Kim</strong>, Soo-Chul Lim<br>
    <span class="pub-venue">Mathematics 2025, 13(22), 3585</span><br>
    DOI: <a href="https://doi.org/10.3390/math13223585" target="_blank">[10.3390/math13223585]</a><br>
    <a href="https://www.mdpi.com/2227-7390/13/22/3585" target="_blank">[Paper]</a>
    <a href="https://www.youtube.com/watch?v=PXLsaaZMp6w" target="_blank">[Video]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img">
    <img src="files/video_prediction_result.gif" alt="Scene Prediction">
  </div>
  <div class="pub-body">
    <div class="pub-title">Prediction of Delay-Free Scene for Quadruped Robot Teleoperation: Integrating Delayed Data with User Commands</div>
    Seunghyeon Ha*, <strong>Seongyong Kim*</strong>, Soo-Chul Lim<br>
    <span class="pub-venue">IEEE Robotics and Automation Letters, vol. 10, no. 3, pp. 2846–2853, March 2025</span><br>
    <span class="pub-venue">IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2025), Oral/Poster Presentation</span><br>
    DOI: <a href="https://doi.org/10.1109/LRA.2025.3536222" target="_blank">[10.1109/LRA.2025.3536222]</a><br>
    <a href="https://ieeexplore.ieee.org/document/10857415" target="_blank">[Paper]</a>
    <a href="https://seongdrgn.github.io/scene-prediction-quadruped/" target="_blank">[Project page]</a>
    <a href="https://www.youtube.com/watch?v=wL9UEJnq53s" target="_blank">[Video]</a>
    <a href="files/IROS2025_Poster.pdf" target="_blank">[Conference Poster]</a>
  </div>
</div>

<div class="pub">
  <div class="pub-img">
    <img src="files/array_tactile.gif" alt="Array Tactile">
  </div>
  <div class="pub-body">
    <div class="pub-title">Effects of Sensing Tactile Arrays, Shear Force, and Proprioception of Robot on Texture Recognition</div>
    Jung-Hwan Yang*, <strong>Seongyong Kim</strong>, Soo-Chul Lim<br>
    <span class="pub-venue">Sensors 23, no. 6: 3201</span><br>
    DOI: <a href="https://doi.org/10.3390/s23063201" target="_blank">[10.3390/s23063201]</a><br>
    <a href="https://www.mdpi.com/1424-8220/23/6/3201" target="_blank">[Paper]</a>
    <a href="https://www.youtube.com/watch?v=l--EEY5fy4g" target="_blank">[Video]</a>
  </div>
</div>

<hr>

<!-- ── Projects ───────────────────────────────────────── -->
<h2>Projects</h2>

<div class="entry">
  <div class="entry-left">Development of Intelligent Autonomous Manipulation Technology for Humanoids with Reduced Dependency on Real-World Data</div>
  <div class="entry-right">Jul 2025 – Present</div>
</div>

<div class="entry">
  <div class="entry-left">Robot Motion Generation AI based on Multimodal Vision/Tactile Information Driven by Language Model</div>
  <div class="entry-right">Mar 2025 – Present</div>
</div>

<div class="entry">
  <div class="entry-left">
    Collecting Large-scale Robot Manipulation Data in Physical Environment<br>
    <a href="https://github.com/seongdrgn/Large-Scale-Robotic-Manipulation-Data-Collection" target="_blank">[Github]</a>
    <a href="https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=71825" target="_blank">[Dataset]</a>
  </div>
  <div class="entry-right">Aug 2024 – Dec 2024</div>
</div>

<div class="entry">
  <div class="entry-left">Development of a High-performance Multimodal Electronic Skin Sensor of Hybrid-type and A Scalable Module for Robot Manipulation</div>
  <div class="entry-right">2021 – 2023</div>
</div>

<hr>

<!-- ── Awards ─────────────────────────────────────────── -->
<h2>Awards</h2>

<div class="entry">
  <div class="entry-left">Best Paper Award, <em>2025 Summer Conference of BK21FOUR AIMS Center</em></div>
  <div class="entry-right">2025</div>
</div>

<hr>

<!-- ── Presentation ───────────────────────────────────── -->
<h2>Presentation</h2>

<div class="entry">
  <div class="entry-left">
    Prediction of Delay-Free Scene for Quadruped Robot Teleoperation: Integrating Delayed Data With User Commands,
    <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</em><br>
    <a href="files/IROS2025_Poster.pdf" target="_blank">[Conference Poster]</a>
  </div>
  <div class="entry-right">2025</div>
</div>

<div class="entry">
  <div class="entry-left">
    Multi-agent Reinforcement Learning for Catching Thrown Object using Pixel-wise Features,
    <em>Workshop in Robot Learning (KROS)</em>
  </div>
  <div class="entry-right">2025</div>
</div>

<hr>

<!-- ── Work Experience ────────────────────────────────── -->
<h2>Work Experience</h2>

<div class="entry">
  <div class="entry-left">Teaching Assistant for Introduction to Intelligent Robotics (Dongguk Univ., MEC4100)</div>
  <div class="entry-right">Mar – Jun 2025<br>Mar – Jun 2024</div>
</div>

<div class="entry">
  <div class="entry-left">Teaching Assistant for Dynamics (Dongguk Univ., MEC2012)</div>
  <div class="entry-right">Sep – Dec 2024<br>Sep – Dec 2022</div>
</div>

</body>
</html>
