---
layout: post
title: "A Tomato Plant You Can Walk Around: 3D Gaussian Splatting for Plant Digital Twins"
date: 2026-11-20
permalink: /blog/gaussian-splat-tomato/
categories: [research, 3d-vision]
tags: [gaussian-splatting, digital-twins, tomatopgt]
---

I've released an interactive 3D Gaussian-splat reconstruction of a **Big Beef Hybrid tomato plant**, captured on May 29, 2026 for **TomatoPGT V2**, the next version of my 3D tomato-plant dataset. You can rotate it, zoom into individual leaves and stems, and see the plant from angles a single camera never captures.

<!--more-->

<a class="splat-poster" href="https://superspl.at/scene/91984dcf" target="_blank" rel="noopener">
  <img src="https://s3-eu-west-1.amazonaws.com/images.playcanvas.com/splat/91984dcf/v1/xl.webp" alt="3D Gaussian splat of a Big Beef Hybrid tomato plant">
  <span class="play">Explore in 3D →</span>
</a>
<p class="small">Click the image to open the interactive viewer on SuperSplat. It runs in the browser; no install needed.</p>

<!-- OPTIONAL: to show the live 3D viewer right here instead of the picture,
     open the scene on SuperSplat, click "Embed", copy the code that starts with <iframe,
     and paste it on the line below this comment. -->

## What you're looking at

3D Gaussian splatting represents a scene as a large set of small, semi-transparent 3D Gaussians, each with a position, shape, colour and opacity. Rendered together, they give a photorealistic view that you can move through in real time, even in a web browser. This reconstruction was built in Agisoft Metashape from multi-view images of a single plant.

## Why it matters for my research

- **Beyond point clouds.** TomatoPGT V1 is a set of annotated point clouds: good geometry, but limited appearance. Splats keep the fine detail of thin structures such as leaflets and petioles, and render realistically from any viewpoint.
- **A richer starting point for digital twins.** My research builds *persistent plant digital twins*: organ graphs that repair the parts a robot cannot see and carry memory from one visit to the next. Splats give both the appearance and the geometry those twins are built from.
- **Simulating what a robot sees.** Because splats can be rendered from any angle, they can show what a robot camera would see from a crop row, and what it would miss. I'm exploring this for testing how well plant structure can be recovered under occlusion.

## Explore and reuse

- **Interactive viewer:** [BBH_1_2026_05_29 on SuperSplat](https://superspl.at/scene/91984dcf)
- **License:** CC BY 4.0, free to reuse with credit.
- **Suggested credit:** Nethala, P. (2026). *BBH_1_2026_05_29: 3D Gaussian splat of a Big Beef Hybrid tomato plant (TomatoPGT V2).* SuperSplat. https://superspl.at/scene/91984dcf
- **Related:** the [TomatoPGT V1 dataset](https://doi.org/10.17632/72md54c7n7.1) and [CloudSeg / CloudGraph code](https://doi.org/10.5281/zenodo.18651881).

Questions or ideas for collaboration? Email me at [nethpras@gmail.com](mailto:nethpras@gmail.com).
