# Right-Hand Rule VR

An interactive VR simulation for practicing the right-hand rule for cross products in introductory electromagnetism, built with Three.js and WebXR for Meta Quest.

Designed and developed by Anthony Danese, high school physics teacher.

## What it does

Students practice applying the right-hand rule for the cross product **F** = q**v** × **B** in an immersive 3D environment. A virtual hand responds to controller orientation — students align the hand to match the velocity and magnetic field vectors, then curl into the correct force direction. Zone-based color and tone-based audio feedback tells students whether their alignment is correct before they commit to the final fist gesture.

## Features

- Tube-rendered virtual hand that mirrors controller orientation
- Velocity and magnetic field vectors displayed in 3D space
- Multi-phase interaction: snap-to-alignment, then fist to confirm
- Zone-based color feedback (correct / close / incorrect)
- Multiple problem configurations

## Controls

| Action | Control |
|---|---|
| Orient hand | Right hand motion (no controller) |
| Confirm answer | Make fist and straighten thumb |
| Next problem | Index-thumb pinch |
| Prediction Mode | Fist shake|

## How to use

1. Open your Meta Quest browser and navigate to the live sim
2. Tap **Enter VR**
3. Read the velocity and field vectors displayed in the scene
4. Rotate your right hand to align the virtual hand
5. Make a fist and straighten thumb to confirm your answer and see feedback

**Live sim:** https://phys-viz.github.io/RHRVR/

## Pedagogical context

This simulation is designed to build spatial intuition for 3D cross products before students work with quantitative magnetic force problems. The multi-phase commit mechanic encourages students to reason carefully rather than guess. It is part of a suite of VR simulations for introductory electromagnetism.

## Tech stack

- **Three.js** r128
- WebXR API
- Vanilla JavaScript — no build tools, no frameworks
- Hosted on GitHub Pages

## License

© 2026 Anthony Danese. Licensed under **CC BY-NC-SA 4.0**.  
Free for educational use. Commercial use requires explicit written permission.
