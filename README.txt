============================================================ EVAC —
EMERGENCY EVACUATION SIMULATOR
============================================================

PROJECT OVERVIEW

EVAC is a browser-based simulation system designed to model real-time
evacuation scenarios in buildings during fire emergencies. It visualizes
fire spread, smoke propagation, and intelligent agent navigation using
AI algorithms.

  ------------------------------------------------------------
  PROBLEM STATEMENT
  ------------------------------------------------------------
  In large buildings such as malls, offices, and hospitals,
  emergency evacuation becomes difficult due to: - Lack of
  real-time guidance - Rapid fire and smoke spread -
  Inefficient human decision-making

  OBJECTIVE: To simulate such emergency scenarios and compute
  the safest and shortest evacuation path using AI-based
  techniques.
  ------------------------------------------------------------

PROPOSED SOLUTION

The EVAC simulator provides: - Real-time environment visualization -
Dynamic fire and smoke behavior - AI-controlled agent navigation -
Intelligent pathfinding using A* and BFS

  ------------------------------------------------------------
  KEY FEATURES
  ------------------------------------------------------------
  - AI Pathfinding (A* and BFS) - Fire Spread Simulation -
  Smoke Propagation System - Animated Agent Movement -
  Multiple Map Layouts: * Mall * Office * Hospital * Maze -
  Interactive Controls (Speed, Wind, Fire Intensity) -
  Real-time Telemetry Dashboard - Audio Alerts (Siren, Alarm,
  PA System)

  ------------------------------------------------------------

ALGORITHMS USED

1.  Breadth-First Search (BFS)
    -   Explores level by level
    -   Guarantees shortest path in grid
2.  A* (A-Star Algorithm)
    -   Uses heuristic for faster pathfinding
    -   More efficient than BFS

Heuristic Used: Manhattan Distance = |x1 - x2| + |y1 - y2|

  ------------------------------------------------------------
  FIRE & SMOKE MODELING
  ------------------------------------------------------------
  - Fire spreads probabilistically - Influenced by: * Fire
  intensity (Low / Medium / High) * Wind direction - Smoke
  diffuses and accumulates over time

  ------------------------------------------------------------

TECH STACK

-   HTML5 Canvas
-   CSS3
-   JavaScript (Vanilla)
-   Web Audio API
-   Speech Synthesis API

  ------------------------------------------------------------
  HOW TO RUN
  ------------------------------------------------------------
  1. Save the code as a .html file 2. Open it in a web browser
  (Chrome recommended) 3. Click “START EVACUATION” 4. Adjust
  controls and observe the simulation

  ------------------------------------------------------------

TEAM MEMBERS

-   Arpit Vishwakarma (23051089)
-   Ayush Raj (23051097)
-   Hari Suryansh Singh (23051107)

  ------------------------------------------------------------
  PROJECT GUIDE
  ------------------------------------------------------------
  Rajdeep Chatterjee

  ------------------------------------------------------------

PROJECT DETAILS

AI Tiny Project B.Tech CSE — 3rd Year

  ------------------------------------------------------------
  FUTURE IMPROVEMENTS
  ------------------------------------------------------------
  - Multi-agent evacuation system - Machine learning-based
  routing - 3D / VR simulation - Crowd behavior modeling

  ------------------------------------------------------------

CONCLUSION

This project demonstrates how AI algorithms and simulation techniques
can significantly improve emergency evacuation strategies and
decision-making.
============================================================
