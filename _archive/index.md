---
layout: default
title: "Home"
permalink: /
---

<section class="hero">
  <div>
    <h1>Robotics + AI Engineer <span class="small">(3D Perception)</span></h1>

    <p class="lead">
      I build <b>end-to-end demos</b> using <b>3D point clouds</b> (Open3D / PyTorch) and robotics tooling (ROS, sensors, control).
      I like shipping practical systems: capture → perception → geometry → action.
    </p>

    <div class="actions">
      <a class="btn primary" href="/projects/">View Projects</a>
      <a class="btn" href="/cv/">View CV</a>
      <a class="btn" href="mailto:your@email.com">Contact</a>
    </div>

    <div class="chips">
      <span class="chip">Point Clouds</span>
      <span class="chip">Open3D</span>
      <span class="chip">PyTorch</span>
      <span class="chip">ROS</span>
      <span class="chip">Robotics Demos</span>
    </div>

    <p class="small" style="margin-top:12px;">
      Seeking internships in <b>Robotics / 3D Vision / Perception / ML Engineering</b>.
    </p>
  </div>

  <div>
    <div class="media">
      <b>Profile photo placeholder</b><br/>
      Add <code>images/profile.jpg</code> later (optional). This box will be replaced by your photo.
    </div>
  </div>
</section>

<hr/>

<h2>Featured Projects (demos first)</h2>

<div class="grid">

  <div class="card">
    <h3>Plant Point Cloud Pipeline → Graph / Phenotyping</h3>
    <div class="meta">Perception • Structure extraction • Metrics</div>
    <p>Pipeline from scan to cleaned point cloud to organ-level structure and phenotype measurements.</p>

    <div class="media">
      Drop your GIF here: <code>images/pointcloud.gif</code><br/>
      (Then we’ll replace this placeholder with the real GIF.)
    </div>

    <div class="card-actions">
      <a class="btn" href="https://github.com/nethpras" target="_blank" rel="noopener">Code</a>
      <a class="btn" href="/projects/">Details</a>
    </div>
  </div>

  <div class="card">
    <h3>Robotic Pruner Demo (Target → Motion)</h3>
    <div class="meta">3D target • Control • Safety</div>
    <p>Detect target in 3D and drive tool motion with repeatable actuation and safety checks.</p>

    <div class="media">
      Drop your MP4 here: <code>videos/demo.mp4</code><br/>
      (Or we can embed YouTube later for faster loading.)
    </div>

    <img class="avatar" src="/images/profile.jpg" alt="Profile photo">
    <p class="small" style="margin-top:10px;">
      <a href="{{ site.social.github }}" target="_blank" rel="noopener">GitHub</a>
      {% if site.social.linkedin and site.social.linkedin != "" %} •
      <a href="{{ site.social.linkedin }}" target="_blank" rel="noopener">LinkedIn</a>
  {% endif %}
</p>

  </div>

</div>

<hr/>

<h2>What I can do for your team</h2>
<ul>
  <li>Build clean pipelines (data → model → evaluation → demo)</li>
  <li>Work with 3D sensors (RealSense/LiDAR) and point cloud processing</li>
  <li>Deliver reproducible code + clear documentation</li>
</ul>
