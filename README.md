# Ilteza's World ✨

A deeply personalized, interactive web experience created from scratch as a digital gift. Designed to be a digital safe space, this application features two distinct UI states—one for exploration and one for relaxation—each packed with custom micro-interactions, animations, and interactive DOM elements.


### Core Features & Mechanics

The application relies on a global state toggle to seamlessly switch between two distinct environments, completely altering the CSS variables, background DOM elements, and interactive grids.

#### Ilteza's Adventures (Day State)
* **Destination Generator:** A dynamic flapper-board animation that randomizes travel destinations and fetches corresponding real-world data.
* **Touch-Optimized Canvas:** A custom 2D HTML5 `<canvas>` implementation featuring a dual scratch-off mechanic to reveal hidden images beneath a digital silver foil. Includes coordinate-scaling math for pixel-perfect mobile touch accuracy.
* **Drag-and-Drop Game:** A packing mini-game utilizing DOM event listeners (`dragstart`, `drop`, `touch`) to pack a virtual suitcase.
* **CSS 3D Transforms:** Interactive travel postcards utilizing `transform-style: preserve-3d` for smooth, realistic flipping mechanics.
* **Particle Physics:** A "Travel Fund" button that triggers dynamically generated, pure-CSS golden coins that fall and fade using cubic-bezier timing functions.

#### Ilteza Mode Activated (Night State)
* **Dynamic Audio Engine:** A centralized `AudioContext` engine built to handle multiple overlapping sound files (Qur'an recitation, ambient nature sounds, and interaction sound effects) while actively bypassing mobile browser autoplay restrictions.
* **Midnight Drawing Board:** A drawing application using HTML5 Canvas that maps mouse and touch coordinates to draw glowing, neon-light trails that programmatically fade out over time using `setInterval` opacity layering.
* **Custom Weather Overlays:** JavaScript-generated DOM nodes that create continuous, randomized rain and snow particle animations across the viewport.
* **Interactive Physics:** Elements like the Fidget Spinner and Wind Chimes utilize complex CSS animations, transform rotations, and pendulum-style keyframes triggered by user interactions.
* **Local Storage Integration:** A "Dream Notes" journaling system that captures user input, renders it into a dynamic masonry grid, and persists the data using the browser's `localStorage` API.

---

### Tech Stack
This project was built entirely without external libraries or frameworks to prioritize lightweight performance and absolute custom control.
* **HTML5** (Semantic structure & Canvas API)
* **CSS3** (CSS variables, flexbox/grid layouts, advanced keyframe animations, 3D transforms, and responsive media queries)
* **Vanilla JavaScript (ES6+)** (State management, DOM manipulation, Web Audio API, and touch-event handling)

---

### Design Philosophy
The goal was to build something that feels less like a standard website and more like a native, tactile mobile app. Every interactive element provides immediate visual or audio feedback, from CSS steam rising out of an aroma diffuser to the precise drop shadows on the interactive buttons. 
