---
title: "XR Development with Godot Engine and Meta Quest 3"
date: 2024-06-15T10:00:00+02:00
layout: ireland-story
caption: "Anchoring virtual worlds to real spaces."
heroImage: "xr-quest.svg"
heroAlt: "Abstract XR field with anchors and waveforms"
heroCredit: "Custom graphic"
description: "VisualAnchors plugin, passthrough rendering, and spatial computing experiments on Quest 3."
draft: false
---

Curiosity about extended reality led me to explore the full capabilities of Godot Engine for Meta Quest 3, including passthrough rendering and mixed-reality interaction.
I studied how the headset’s cameras, sensors, and coordinate systems operate, and how Godot’s XR architecture manages spatial mapping and tracking.

During this exploration, I developed VisualAnchors, a custom plugin that extends Godot with real-world anchoring through QR-code detection and pose estimation.
The system uses a native OpenCV backend on Android to identify markers, estimate their 3D poses via IPPE (SOLVEPNP_IPPE_SQUARE), and project them into Godot’s XR space with smoothing filters such as One-Euro and SLERP.
It provides a high-level VisualAnchorsManager API that allows developers to bind 3D nodes directly to real-world anchors, creating a seamless bridge between the physical and virtual environments.

This work gave me a deep understanding of how computer vision, geometry, and XR systems can merge into spatial computing.
It also taught me the discipline of building cross-platform, performance-oriented tools that enable others to experiment and create.

🔗 VisualAnchors on GitHub

https://github.com/davoddino/visualanchors

⸻
