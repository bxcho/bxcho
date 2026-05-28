## 🛠️ Featured Software Engineering Projects

### 🎮 2D Tile-Based World Exploration Engine (UC Berkeley CS 61B)
*Collaborative Software Engineering Project | Completed Spring 2026*

### 🚀 Project Overview & Product Development Cycle
Developed a pseudo-random, deterministic 2D world generation and exploration engine in Java. Built with minimal starter code, this project simulated a full industry product development cycle—moving from open-ended ideation to architectural design, state management implementation, and final presentation. 

Rather than focusing strictly on isolated algorithms, the core challenge of this project was **managing code complexity and mitigating technical debt** in a large software system. The project was explicitly evaluated using a framework mimicking a Silicon Valley internship performance review.

* **Core Tech:** Java, Data Structures, StdDraw Graphical Engine, Object-Oriented Design (OOD)
* **Architecture Style:** Decoupled Engine Core (Logic) from the UI Rendering Layer

### 🛠️ Key Engineering Implementations

* **Deterministic World Generation:** Designed a random-world generation system tied to a user-inputted seed. Leveraged custom graph-traversal and tile-placement rules to ensure all generated rooms, walls, and hallways connected seamlessly without overlaps, creating a fully explorable and unique map every run.
* **State Management & Persistence:** Built a robust serialization system capable of saving the exact state of the world and loading it back seamlessly. Implemented both a live keyboard-interactivity loop and a key-stroke string history parser to replay inputs identically.
* **UI & User Experience (UX):** Created an interactive main menu, a live Heads-Up Display (HUD) that dynamically displays text descriptions of tiles upon mouse hover, and modular exploration controls.
* **Refactoring & Architectural Design:** Actively managed software complexity by breaking down monolithic methods into highly modular, reusable helper functions, preventing the codebase from becoming fragile or expensive to maintain.

*(Note: In strict compliance with UC Berkeley academic integrity and course anti-cheating policies, the raw Java source code is maintained in a private repository. Video demonstration and architectural walkthrough are available upon request.)*
