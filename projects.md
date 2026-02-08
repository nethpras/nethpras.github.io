---
layout: default
title: "Projects"
permalink: /projects/
---

# Projects

<p class="small-note">
Each project: <b>Problem → Approach → Result → Demo → Links</b>.
</p>

<div class="grid">

  <div class="card">
    <h3>Plant Point Cloud Pipeline</h3>
    <div class="meta">Open3D • segmentation • graph extraction</div>

    <p><b>Problem:</b> Organ-level understanding from plant scans.</p>
    <p><b>Approach:</b> Capture + filtering + annotation + structure extraction.</p>
    <p><b>Result:</b> Clean organ-level outputs + phenotype metrics (angles/lengths/volume).</p>

    <p><img src="/images/pointcloud.gif" alt="pointcloud demo"></p>

    <div class="card-actions">
      <a class="btn" href="https://github.com/nethpras" target="_blank" rel="noopener">GitHub</a>
      <a class="btn" href="/blog/">Write-up</a>
    </div>
  </div>

  <div class="card">
    <h3>Robotic Pruner Demo</h3>
    <div class="meta">Arduino • motion control • safety</div>

    <p><b>Problem:</b> Reliable actuation for pruning actions.</p>
    <p><b>Approach:</b> Control logic + limit checks + repeatable step motion.</p>
    <p><b>Result:</b> Consistent tool strokes and safer operation.</p>

    <video controls>
      <source src="/videos/demo.mp4" type="video/mp4">
    </video>

    <div class="card-actions">
      <a class="btn" href="mailto:your@email.com">Request full demo</a>
    </div>
  </div>

</div>

<hr>

## Add a new project
Copy one `<div class="card"> ... </div>` block, change:
- title
- problem/approach/result
- demo (image/gif/video)
- GitHub link
