# Project Description: F1 Interactive Analytics Portfolio

## 🏎️ Core Concept

An interactive, low-poly 3D web application designed for US Admissions Officers. Utilizing a racing telemetry metaphor, the project presents deep intellectual insights, leadership reflections, and personal growth across four distinct sectors (Academics, Mathematics, Coding, and Volunteering) rather than a flat list of achievements.

## 🛠️ Technical Architecture

* **Engine:** Three.js (Vanilla JS) optimized for real-time 3D rendering of unified low-poly assets.
* **Controls & Navigation:** Constraint-based spline mechanics (`CatmullRomCurve3`) tied exclusively to `W/S` or Arrow keys to guarantee zero-friction exploration.
* **Cinematics & UX:** Dual-camera matrix supporting an automated Third-Person Follow Mode and an interactive Orbit Inspection Mode.
* **Frontend UI:** High-contrast responsive HUD overlay rendering simulated speed metrics, lap tracking, and dynamic modal panels for content delivery.

## 🎯 Antigravity Integration Strategy (Gemini 2.5 Pro)

* **BYOK Deployment:** Connect native API keys via Google AI Studio to leverage Gemini 2.5 Pro’s 2-million token window.
* **Agentic Refactoring:** Utilize context-aware prompts to handle multi-file syncs, vector math adjustments for the track curve, and glTF mesh extraction operations.

---

**Immediate Action:** Load the unified `.glb` model into the directory, verify the exact mesh name for the vehicle extraction loop, and compile the `index.html` structure to initiate route calibration.
