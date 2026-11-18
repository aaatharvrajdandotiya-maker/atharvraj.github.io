# Architectural Evaluation: Vanilla HTML/CSS/JS vs Vite vs React

After analyzing the requirements—GitHub Pages static deployment, zero backend dependencies, absolute performance, high-end editorial typography, and precise layout control—**Vanilla HTML5, modern CSS3 (Grid/Flexbox/Custom Properties), and lightweight modern JavaScript (ES Modules)** is the absolute best choice.

### Why Vanilla Wins Here:
1. **Zero Build Overhead**: No unnecessary bundlers, JSX compilation steps, or node module bloat. Directly deployable to GitHub Pages.
2. **Instant Paint & Performance**: Eliminates JavaScript bundle parsing overhead on mobile. The browser renders semantic HTML and CSS instantly.
3. **Precision Design Control**: Direct control over DOM rendering, custom cursor states, and GSAP/ScrollTrigger integrations without framework reconciliation cycles.
4. **Clean Codebase**: Matches the high standard of your *Chambal Thrift* source code.

We will structure the project cleanly with native ES modules for script partitioning if needed, but a robust single `index.html` (with embedded high-performance CSS and modular vanilla JS) guarantees instant loading and absolute reliability.
