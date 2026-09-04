# Flluid Studio

A single-file WebGL fluid-shader card interaction prototype.

Flluid Studio explores how a compact interface can make shader parameters feel tangible: one central fluid card, motion choices on one side, color themes on the other, and animated connection lines that make the selected state feel connected to the object it controls.

## What It Does

- Renders a 256 x 256 fluid card with a real-time Three.js fragment shader.
- Lets the viewer switch between motion modes: Still, Wave, and Storm.
- Lets the viewer switch between color themes: Mist, Ocean, and Abyss.
- Uses animated SVG connector lines between controls and the card.
- Adapts to mobile by switching layout and reducing visual complexity.
- Supports keyboard interaction and `prefers-reduced-motion`.

## Why It Matters

This is a small interaction prototype, but it shows a useful product-building instinct: making abstract visual settings readable through direct manipulation and stateful feedback.

The prototype is strongest as evidence for:

- Creative coding
- Shader-based UI exploration
- Interaction states
- Accessible motion controls
- Turning a visual reference into a reusable interface pattern

## Implementation Notes

- No build step required.
- The demo runs from `index.html`.
- Rendering uses Three.js from a CDN.
- Motion transitions use GSAP from a CDN.
- The shader is clipped inside a rounded card and layered with glow, inner highlight, and inner shadow treatments.

## Attribution

This project references [`napnow/fluid-shader-card`](https://github.com/napnow/fluid-shader-card) as its source base. Keep that attribution when publishing.

## Recommended Repo Description

Single-file WebGL fluid-shader card prototype with motion/theme controls, animated connectors, and accessible interaction states.

## Suggested Topics

`webgl`, `threejs`, `shader`, `creative-coding`, `interaction-design`, `prototype`, `design-engineering`
