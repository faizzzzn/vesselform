# VESSELFORM — Precision Vessel Studio

A single-use micro-tool for exploring vessel and bottle forms: draft a profile with CAD precision, shape it with exact numbers, finish it in studio materials, export it to any 3D app.

Sparked by Hector Rodriguez's disposable-tool idea — one tiny tool per concept direction, retired when the concept is resolved.

## Install

Open **https://faizzzzn.github.io/vesselform/** in Edge or Chrome → **Install**.

It lands on your PC as a real app — own window, Start menu entry — and works offline after the first load. Free, no signup.

(Needs internet the first time you open it: the 3D engine loads from a CDN.)

## What it does

- **Draft view** — AutoCAD-style precision: crosshair cursor with live coordinates, real dimension lines, square grips, snap/grid, and a properties palette with exact numbers
- **Command line** — type `HEIGHT 280`, `PRESET`, `EXPORT GLB`, or `HELP`
- **Shape** — form controls in plain words: Height, Width, Lean, Edges, Ridges, Twist, Squash
- **Surface** — colour and shine, with palettes suggested from colour theory
- **Scene** — studio backdrops pulled live from a CC0 library
- **Export** — STL, OBJ, and GLB. They open in Blender, Rhino, anything.

## Tech

One self-contained page (HTML + PWA manifest + service worker). No build step, no account, no server.

---

© Faizan. All rights reserved.
