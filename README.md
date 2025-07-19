#  Mukwaya Lwere’s Animation Simulator 

##  Project Overview

As part of **CS 81: JavaScript – Module 7A Code Review**, *Mukwaya Lwere* created the **Animation Simulator**. This interactive web project uses a fun and captivating loading animation to show off asynchronous JavaScript behavior.

Users are presented with a spinning character sequence that mimics a loading process when the page loads. When the animation is finished, a happy sound is played, a message congratulating the viewer is displayed, and the background color changes to signify success. For ongoing enjoyment, there is also a convenient button to restart the simulation.
---

##  How It Works

- Cycles through spinner frames using `setInterval()`: `["|", "/", "-", "\\"~
- With smooth {200ms` intervals, it runs for `8` full loops.
- It loads the celebratory end state and updates the visual status.
- The `<audio>` tag is used to play a sound upon completion. 
- A **"Try That Again"** button is included to restart the animation.

---

##  Learning Objectives

- Practice using JavaScript timing functions that are asynchronous.
- Investigate event handling and DOM manipulation; 
- comprehend UX feedback components such as interactivity and status messaging;
- and use multimedia elements (sound and visual cues).

---

##  Files in This Repository

- `loadingAnimation.html` – Main HTML file with embedded animation script
- `REFLECTION.md` – Personal reflection documenting challenges, learnings, and improvements
- `RESULTS.md` – Summary of outcomes and performance of the animation sequence

---
---

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mlwere1977/cs81-module7a-animation.git
   Website: https://mlwere1977.github.io/cs81-module7a-animation/loadingAnimation.html