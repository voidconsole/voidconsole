# PROJECTS

A collection of systems, simulations, experimental infrastructure, embedded hardware, and computational research projects exploring emergence, uncertainty, control, physics, and first-principles engineering.

---

### **[TARS](https://www.google.com/search?q=https://github.com/voidconsole/tars)** *(In-Progress)*

A stochastic-temporal general-purpose programming language and runtime ecosystem where uncertainty, distributions, tensors, lattices, and time exist as first-class computational primitives.

* **Core Paradigm:** Replaces standard random libraries by embedding non-deterministic state directly into language semantics via *Fluxions* (unresolved probabilistic states), resolved at evaluation time through *Collapse* operations.
* **Data Architecture:** Introduces *Lattices* as primitives to natively handle matrices, tensors, and datasets without external scaling abstractions.
* **Key Features:** Fluxions (`30 ~ 5`), probabilistic conditionals, collapse semantics (`<x>`), lattice systems, temporal operations, and pipeline-based transformations.
* **Tooling Infrastructure:** The complete ecosystem; including the website, VS Code extension, Node-based CLI, and companion applications; is maintained in `tarsx`.

**Tech:** JavaScript, Compiler Design, ASTs, Language Engineering, Scientific Computing

---

### **[DEVOID](https://www.google.com/search?q=https://github.com/voidconsole/devoid)**

A self-hosted, zero-knowledge communication infrastructure built entirely without third-party messaging services, centralized platforms, or cloud dependency.

* **Cryptographic Architecture:** Implements a layered security model featuring TLS transport security via NGINX, ephemeral X25519 session derivation, and AES-256-GCM pairwise end-to-end encryption.
* **Trust Minimization:** Built on a blind-router server architecture physically hosted on a Raspberry Pi; the backend mathematically cannot decrypt user payloads as it never possesses the required shared secrets.
* **System Capabilities:** Features self-hosted WebSocket infrastructure, dynamic media re-decryption, zero-knowledge messaging, and SQLite WAL-based persistence.
* **Client App:** Interface designed around a hyperminimalist, custom-built Flutter client for real-time encrypted messaging.

**Tech:** Flutter, Node.js, Cryptography, WebSockets, SQLite, NGINX, Raspberry Pi

---

### **[FLUID ENGINE](https://www.google.com/search?q=https://github.com/voidconsole/fluid-sim)**

A research-oriented particle simulation engine investigating whether macro-scale fluid phenomena can emerge purely from localized collision laws without relying on Navier–Stokes equations.

* **Bottom-Up Mechanics:** Bypasses direct programming of pressure, viscosity, turbulence, or thermal systems. The engine calculates only discrete elastic particle collisions, allowing macro behaviors to emerge from local momentum transfer.
* **Demonstrated Phenomena:** Successfully simulates vortices, pressure fronts, thermal diffusion, momentum waves, shear instability, Bernoulli-like effects, and emergent turbulence.
* **Control:** Every experiment modifies only the initial particle distribution logic while the underlying collision engine remains completely identical.

**Tech:** JavaScript, p5.js, Physics Simulation, Particle Dynamics, Emergent Systems

---

### **[COLLISION](https://www.google.com/search?q=https://github.com/voidconsole/collision)**

A lightweight 2D collision and particle physics engine built entirely from first principles to understand the primitive mechanics underlying simulation systems.

* **Physics Core:** Manually handles elastic collisions, momentum transfer, overlap correction, boundary constraints, and particle interaction systems using vector mathematics and geometric collision resolution.
* **Integration:** Acts as the foundational computational engine powering Fluid-Sim and related velocity-based experiments.
* **Experimental Modes:** Includes alternate interaction laws that produce non-standard emergent behaviors, such as orbit-like and chaotic particle dynamics.

**Tech:** JavaScript, Computational Physics, Vector Mathematics, Simulation Systems

---

### **[ACCELERUS](https://www.google.com/search?q=https://github.com/voidconsole/control-system)** *(In Progress)*

An autonomous rocket ascent and descent flight computer featuring active aerodynamic stabilization and guided recovery systems.

* **Control Architecture:** Designed around a multi-stage aerospace control loop utilizing real-time sensor fusion and embedded logic to guide the vehicle through changing aerodynamic regimes.
* **Flight Pipeline:** Manages active fin stabilization during ascent, executes autonomous flight-state transitions, triggers apogee detection, deploys a parasail, and runs GPS-guided descent logic.
* **System Goal:** Establishes a reusable autonomous recovery architecture capable of landing hardware near predetermined coordinates post-launch.

**Tech:** Embedded C, PID Control, GPS Systems, Flight Control, Embedded Systems

---

### **[MAGLEV GLOBE](https://www.google.com/search?q=https://github.com/voidconsole/maglev-globe)**

A magnetically levitating, Bluetooth-controlled interactive globe combining custom embedded hardware, geolocation mapping, and rotational control loops.

* **Hardware Integration:** Achieves stable levitation via magnetic dipole pairing, while a hidden continuous-rotation servo drives physical orientation beneath the magnetic field.
* **Feedback Solution:** Because continuous servos lack native positional feedback, the system implements custom rotational sensing and calibration logic to run timing-based RPM reconstruction.
* **App Interaction:** Selecting a country within the Flutter-based Bluetooth client calculates coordinate mapping, triggers the firmware to rotate the globe precisely to that coordinate, and synchronizes RGB lighting to match the country's flag colors.

**Tech:** Arduino, Flutter, Bluetooth, Embedded Systems, Servo Control, Magnetic Levitation

---

### **[VARZONE](https://www.google.com/search?q=https://github.com/voidconsole/varzone)**

A real-time multiplayer debate arena that transforms structured intellectual discussion into a state-driven competitive system.

* **State Management:** Utilizes synchronized state logic to enforce strict debate transitions, faction systems, and live scoring.
* **Role-Based Interaction:** Organizes real-time communication into an interactive structure across four distinct user roles: Orators, Judges, Spectators, and AI Moderators.
* **Evaluation Engine:** Integrates live user voting streams alongside optional AI-based judging and evaluation logic to map collaborative reasoning pathways.

**Tech:** React, Firebase, Real-Time Systems, AI Integration

---

### **[SONARIUM](https://www.google.com/search?q=https://github.com/voidconsole/sonarium)** *(In Progress)*

An experimental procedural audio engine that maps spatial movement into dynamically layered musical environments to explore continuous emotional spectra.

* **Coordinate-Based Audio:** Replaces discrete track selection by treating emotional profiles as a navigable coordinate space.
* **Dynamic Synthesis:** Mouse movement and spatial coordinate tracking dynamically blend and morph layered audio systems via interactive sound synthesis.
* **Interface Goal:** Builds an affective computational interface where users navigate through fluid emotional landscapes rather than static media.

**Tech:** JavaScript, Procedural Audio, Interactive Systems, Sound Design

---

### **[NANOWATCH](https://www.google.com/search?q=https://github.com/voidconsole/nanowatch)**

An open-source embedded smartwatch platform focusing on compact hardware engineering and hardware state management under tight constraints.

* **Hardware Integration:** Runs custom firmware to manage a physical button interface, low-power state logic, and an external TM1637 display module.
* **System Capabilities:** Embeds local calculator utilities, customizable UI presentation modes, and programmable interaction logic.
* **Connectivity:** Exposes BLE communication layers for real-time interaction and data passing with external devices.

**Tech:** Arduino, BLE, Embedded Systems, Hardware Design

---

### **[WASHWARE](https://www.google.com/search?q=https://github.com/voidconsole/washware)**

Custom firmware for a fully programmable washing machine motherboard structured around finite-state machine architectures.

* **Hardware Control:** Interfaces directly with low-level appliance hardware, orchestrating motor systems, water valves, rinse cycles, and wash timing configurations.
* **Safety Engineering:** Embedded with strict hardware safety constraints, mapping hardware feedback logic and safety interlocks directly into the state transitions to protect system components.

**Tech:** Embedded C++, FSM Architecture, Hardware Control Systems

---

### **[CUSTOM CANVAS](https://www.google.com/search?q=https://github.com/voidconsole/custom-canvas)**

A deliberately unconventional rendering engine that recreates Processing.js-style graphics pipelines entirely out of dynamically generated HTML elements and CSS transitions.

* **Architectural Experiment:** Bypasses the native HTML5 `<canvas>` API completely. Every graphical primitive is instantiated as a positioned DOM element updated in real time via JavaScript.
* **System Benchmark:** Explores browser rendering limits, spatial composition, and DOM-driven animation behavior to isolate what fundamentally constitutes a graphics engine beneath standard abstractions.

**Tech:** HTML, CSS, JavaScript, DOM Rendering Systems

---

### **[MATRIX](https://www.google.com/search?q=https://github.com/voidconsole/matrix)**

A 2D rendering experiment exploring how artificial depth perception can emerge within flat space without true 3D rendering environments.

* **Perceptual Logic:** Generates the illusion of 3D depth by establishing explicit mathematical relationships between size, distance, and speed.
* **Kinematic Scaling:** Applies perspective scaling and motion parallaxobjects closer to the viewer scale larger and move faster, while distant objects scale down and move slower to synthesize spatial depth.

**Tech:** JavaScript, Processing.js, Motion Simulation, Spatial Rendering

---

### **[NOWYOUSEEME](https://www.google.com/search?q=https://github.com/voidconsole/nowyouseeme)**

A physical science-gallery installation demonstrating the observer effect and probabilistic collapse through mechanical, real-time hardware interaction.

* **Mechanical Logic:** Features motor-driven rotating mirrors that spin continuously until a user actively interacts with or observes the system.
* **State Resolution:** Upon observation, a randomized stopping mechanism triggers, instantly halting motion and forcing a single random mirror to face the userserving as a physical analogy for a system collapsing from uncertainty into a resolved state.

**Tech:** Physical Computing, Interactive Systems, Conceptual Installation Design

---

### **[AUTOPOST](https://www.google.com/search?q=https://github.com/voidconsole/autopost)**

An automated social pipeline built to analyze, generate, and distribute content while mimicking non-deterministic human posting behavior.

* **Automation Mechanics:** Orchestrates public APIs and generative AI engines through automated execution pipelines.
* **Timing Logic:** Bypasses rigid cron scheduling in favor of randomized scheduling and behavioral timing logic to introduce natural variation into output distribution.

**Tech:** Python, APIs, Automation Systems, AI Integration

---

### **[TARSX](https://www.google.com/search?q=https://github.com/voidconsole/tarsx)**

The developer tooling infrastructure and official VSCode extension for the TARS programming language ecosystem.

* **Language Tooling:** Establishes the core foundation for syntax highlighting, parsing passes, diagnostics, and semantic analysis directly within the IDE workspace to support the broader language runtime.

**Tech:** VSCode Extensions, JavaScript, Language Tooling

---

### **[SMARTLIGHT](https://www.google.com/search?q=https://github.com/voidconsole/smartlight)**

A dual-state ambient RGB lighting system that dynamically synchronizes physical environments with real-time digital screen states.

* **Ambient Pipeline:** Uses Python-driven screen capture and parsing to extract real-time color values, passing data wirelessly to custom embedded hardware.
* **Hardware Actuation:** The receiving firmware processes inputs to drive RGB control arrays, generating an adaptive ambient response based on environmental and screen conditions.

**Tech:** Python, Embedded Systems, RGB Control

---

### **[COSMIC CIRCUITS](https://www.google.com/search?q=https://github.com/voidconsole/cosmic-circuits)**

The official frontend application and digital identity built for Blueprint, a hardware-focused hackathon based in Bengaluru.

* **Design Implementation:** Prioritizes a highly responsive, hardware-oriented visual architecture focused on clean responsive layouts, event timeline presentation, and interaction design.

**Tech:** HTML, CSS, JavaScript, UI Design

---

### **[SUDOKU ALGORITHM](https://www.google.com/search?q=https://github.com/voidconsole/sudoku-algorithm)**

A JavaScript deductive solving engine focused on logical constraint propagation rather than brute-force recursive backtracking.

* **Constraint Solving:** Maps the board as a possibility space, continuously calculating the All Possible Values (APV) for every unsolved cell across intersecting rows, columns, and 3×3 blocks.
* **Deductive Engine:** As constraints propagate dynamically through the board matrix, the algorithm refines remaining valid states until a deterministic solution emerges naturally.
* **Visualization:** Features real-time APV mapping to make the internal reasoning steps of constraint deduction visually transparent.

**Tech:** JavaScript, Constraint Solving, DSA, Algorithm Design, Interactive Visualization

---

# Agent-Assisted Development Benchmarks

*Projects built specifically to evaluate code generation limits, implementation accuracy, and architectural compliance across various Large Language Models.*

### **[WORMHOLE](https://www.google.com/search?q=https://github.com/voidconsole/wormhole)**

An encrypted, ephemeral web communication platform focused on disposable, low-friction interaction spaces.

* **Implementation:** Experimented with rapid deployment of real-time data synchronization across anonymous room instances, handling temporary message states and transient user sessions without permanent storage.

**Tech:** JavaScript, Firebase, Realtime Communication Systems

---

### **[BRICK](https://www.google.com/search?q=https://github.com/voidconsole/brick)**

An experimental mobile prototype testing rapid system generation, native notification lifecycles, and notification customization through automated assistant workflows.

* **Benchmark Evaluation:** * *Strengths:* Achieved highly refined UI execution and clean interaction design generation.
* *Weaknesses:* Generated flawed background notification lifecycle management, paired with inaccurate documentation usage regarding Flutter's native hardware bridging APIs.



**Tech:** AI-Assisted Development, Rapid Prototyping, Experimental Systems

---

### **[SPOTIFY DASHBOARD](https://www.google.com/search?q=https://github.com/voidconsole/spotify-dashboard)**

A backend-focused analytics tool designed to interface with the Spotify API for music trend aggregation and data visualization workflows.

* **Benchmark Evaluation:**
* *Strengths:* Executed accurate API orchestration, stable backend data processing pipelines, and structured payload parsing.
* *Weaknesses:* Resulted in sub-optimal, rigid layout hierarchy and poor user experience (UX) architectural flow.



**Tech:** JavaScript, APIs, Backend Systems, Data Analysis
