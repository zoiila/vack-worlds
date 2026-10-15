<p align="center">
  <img src="./assets/vack-worlds-banner.svg" alt="Vack Worlds — independent minigame worlds" width="100%">
</p>

# Vack Worlds | Vack Studio

World management and isolated schematic-based minigame instances for Minecraft 26.2.

- Register reusable named schematic templates, inspect their dimensions, and configure relative bounds and spawn points.
- Create an independent temporary world for each match through a Request/Lease API.
- Prepare blocks in bounded batches, track session ownership, and safely release or recover owned worlds.
- Keep original schematic files and manually configured worlds protected from temporary-instance cleanup.
- Retain existing world commands and the earlier whole-world API.
- Compact English admin presentation in the Vack Studio style.

The **1.1.0-preview.1** update targets Java 25 and Paper 26.2; its schematic workflow requires WorldEdit 7.4.6. Compilation, safety tests, isolated Paper lifecycle checks and graceful restart recovery were exercised. Real-player/client acceptance and production profiling remain pending. Leaf, Folia, FAWE and other platform combinations are not claimed as verified.

This page presents the project and its features. Development source, technical documentation and current versioned artifacts are maintained separately.

Developed by Vack Studio.  
Copyright (c) Vack Studio. All rights reserved.
