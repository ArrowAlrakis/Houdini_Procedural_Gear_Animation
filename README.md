# Houdini Procedural Automata

**Author**: Arrow Lyu  
**Software**: Houdini  
**Project Type**: Procedural Modeling / Environment Generation  
**File**: `Procedural_Automata_v08.hipnc` 

---

## Overview

This project showcases a fully procedural automata rig of a mechanical dragon designed and animated in Houdini. Inspired by RadugaGrad's automata concept, the mechanism is controlled entirely by VEX code and procedural logic without any keyframe animation. It was created as a technical exercise in simulating mechanical behavior for use in real-time applications or stylized animation, showcasing a combination of procedural modeling, attribute control, and trigonometric-driven rigging.

[Preview](./Preview.jpg)

[Project Breakdown](./Houdini_Automata_Breakdown.pdf)

▶ Watch the automata demo video: [Download .mp4](./Procedural_Automata_Demo.mp4)

---

##  Features

-  100% procedural system — no keyframes used
-  Functional gear hierarchy — motion propagates with correct ratio
-  Driven by VEX and expressions — uses math for angle calculation and linkage logic
-  Traced 2D parts from image input — procedural base geometry
-  Easy to modify — works by manipulating core parameters (rotation speed, gear teeth, etc.)

---

##  Technical Breakdown

[Project Breakdown](./Houdini_Automata_Breakdown.pdf)

###  Part Construction

- Used Trace SOP to import 2D silhouettes (drawn in Photoshop) and convert them into usable geometry.
- Simplified point count for animation efficiency.

###  Gear Animation

- Gear rotation is propagated using expressions

