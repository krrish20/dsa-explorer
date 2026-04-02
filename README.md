# 🚀 DSA Explorer: Interactive Algorithmic Laboratory

![DSA Explorer Preview](<img width="2920" height="1660" alt="Image" src="https://github.com/user-attachments/assets/a386cd7e-99f9-48ba-bab1-fa6f23762ec0" />) 
![Status](https://img.shields.io/badge/Status-Production--Ready-4FFFE5?style=for-the-badge)

**DSA Explorer** is a high-performance, browser-based pedagogical tool designed to bridge the gap between theoretical data structures and runtime execution. It provides deep, frame-buffered visualizations that allow students to analyze, scrub, and "benchmark" algorithms in real-time.

---

## 🏗️ Core Architectural Features

### ⚡ Overclock: The Big-O Stress Tester
Unlike standard visualizers that slow down for animations, **Overclock Mode** bypasses the DOM to execute raw JavaScript logic on up to **50,000 elements**. It visually proves the massive performance gap between $O(N \log N)$ and $O(N^2)$ algorithms through hardware-locked scaling benchmarks.

### ⏱️ Time-Travel Scrubber
Every algorithmic step is captured into a **frame-buffered state manager**. This enables a dedicated "Timeline" slider, allowing users to pause an execution, scrub backwards to a previous comparison, and replay critical logic sequences frame-by-frame.

### 📐 Dynamic Graph & Tree Builder
*   **Canvas Interaction:** Double-click to spawn nodes, drag-and-drop to draw edges.
*   **Real-time Adjacency Mapping:** The system dynamically re-compiles your custom drawing into an Adjacency List for instant **Dijkstra** or **BFS/DFS** execution.

---

## 🧠 Advanced Educational Tools

- **📊 Live Telemetry HUD:** Real-time counters for **Comparisons**, **Array Writes**, and **Memory Swaps** that reversal-calibrate automatically during scrubbing.
- **🖼️ Code-Trace PIP:** A synchronized Picture-in-Picture window that highlights the exact line of Python/JS pseudocode as the visualizer processes variables.
- **🔗 LeetCode URL Parser:** Enter any LeetCode problem URL to automatically configure the sandbox with appropriate data structures (Two-Pointers, Sliding Window, DP Grids, etc).
- **🕸️ 2D/3D DP Grids:** Detailed visualization for Knapsack, LCS, and Fibonacci with **Bezier-curve data flow tracing** to see exactly how subproblem values populate the matrix.

---

## 📱 Mobile & Premium UX

- **Responsive Design:** Fully optimized for mobile with touch-draggable PIP windows and collapsible topic grids.
- **Glassmorphism UI:** A modern, dark-themed interface built with Vanilla CSS variables and high-frequency CSS animations.
- **⏺️ Video Export:** Built-in `MediaRecorder` pipeline to capture and export your algorithm traces as high-quality **.webm** files for sharing or study.

---

## 🚀 How to Run

1.  **Direct Access:** Open `dsa visualizer.html` in any modern web browser.
2.  **Hosting:** Simply push this repository to **GitHub Pages** to host it as a static site. No build process or dependencies required—it is pure ES6 JavaScript, HTML5, and CSS3.

---

## 🛠️ Tech Stack
- **Engine:** Asynchronous ES6 Promises + `StateManager` Pattern.
- **UI:** Vanilla CSS3 (Custom Properties), Glass-morphism, Flexbox/Grid.
- **Export:** `html2canvas` + `MediaRecorder` API.
- **Logic:** Adjacency List Compilation, BST/AVL Rebalancing, 2D Matrix DP.

---

*“Algorithms are just ideas until you see them move.”* — **Built for the next generation of engineers.** 🎓

