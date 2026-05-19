# PROJECTS

A collection of systems, simulations, experimental infrastructure, embedded hardware, and computational research projects exploring emergence, uncertainty, control, physics, and first-principles engineering.

---

# TARS 
> (In-Progress)
A stochastic-temporal programming language where uncertainty, distributions, tensors, lattices, and time exist as first-class computational primitives.

TARS introduces a new execution paradigm based around *Fluxions* (unresolved probabilistic states)  and *Collapse*, a sampling operation that resolves uncertainty into deterministic values at evaluation time. 
Instead of treating randomness as a library feature, TARS embeds uncertainty directly into the semantics of the language itself. Besides Fluxions, it introduces new datatypes called Lattices, for implementing Matricies, Tensors, Datasets and other features.

The language is designed to unify:
- deterministic computation
- stochastic systems
- scientific computing
- AI systems
- simulations
- procedural generation
- temporal logic

Key features include:
- Fluxions (`30 ~ 5`)
- probabilistic conditionals
- collapse semantics (`<x>`)
- tensor/lattice systems
- temporal operations
- native mathematical abstractions
- pipeline-based transformations
- hybrid deterministic/stochastic execution

The project explores what programming looks like when computation operates not only on values, but on evolving unresolved systems.

**Tech:** JavaScript, Compiler Design, ASTs, Language Engineering, Scientific Computing

---

# DEVOID

A self-hosted zero-knowledge communication infrastructure built entirely without third-party messaging services or cloud dependency.

Devoid uses a layered cryptographic architecture:
- TLS transport security through NGINX
- ephemeral X25519 session derivation
- AES-256-GCM pairwise end-to-end encryption
- blind-router server architecture

The server is physically hosted on a Raspberry Pi and mathematically cannot decrypt user messages because it never possesses the required shared secrets.

The system was built around the idea that communication infrastructure should remain functional even without dependency on centralized platforms or corporations.

Key features:
- self-hosted WebSocket infrastructure
- ephemeral key exchange
- dynamic media re-decryption
- zero-knowledge messaging
- custom Flutter client
- SQLite WAL-based persistence
- real-time encrypted messaging
- hyperminimal interface design

The project explores infrastructure sovereignty, privacy, and cryptographic trust minimization.

**Tech:** Flutter, Node.js, Cryptography, WebSockets, SQLite, NGINX, Raspberry Pi

---

# FLUID-SIM

A research-oriented particle simulation engine exploring whether real fluid phenomena can emerge solely from localized collision laws without using Navier–Stokes equations.

Instead of programming pressure, viscosity, turbulence, or thermal systems directly, the engine simulates only elastic particle collisions. Large-scale fluid behavior then emerges naturally from local momentum transfer between particles.

The simulation successfully demonstrates:
- vortices
- pressure fronts
- thermal diffusion
- momentum waves
- shear instability
- Bernoulli-like effects
- emergent turbulence

Each experiment modifies only the particle initialization logic while the collision engine itself remains identical.

The project serves as an exploration into emergence, computational physics, and bottom-up simulation systems.

**Tech:** JavaScript, p5.js, Physics Simulation, Particle Dynamics, Emergent Systems

---

# COLLISION

A lightweight 2D collision and particle physics engine built entirely from first principles.

The engine handles:
- elastic collisions
- momentum transfer
- overlap correction
- particle interaction systems
- boundary constraints
- experimental interaction laws

Collision acts as the foundational engine powering Fluid-Sim and several other simulation experiments.

Instead of relying on existing physics libraries, the project rebuilds collision behavior manually using vector mathematics and geometric collision resolution to better understand the primitive mechanics underlying simulation systems.

The engine also includes experimental alternate interaction modes that produce emergent orbit-like and chaotic particle behaviors.

**Tech:** JavaScript, Computational Physics, Vector Mathematics, Simulation Systems

---

# CONTROL-SYSTEM *(In Progress)*

An autonomous rocket ascent/descent control system with guided recovery and active stabilization.

The project is designed around a multi-stage aerospace control architecture:
- active fin control during ascent
- autonomous flight-state transitions
- apogee detection
- parasail deployment
- GPS-guided descent and landing

The system uses multiple PID control loops and embedded control logic to stabilize and navigate the rocket through different aerodynamic regimes.

The goal is to create a reusable autonomous recovery system capable of landing near predetermined coordinates after launch.

The project explores:
- embedded aerospace systems
- control theory
- autonomous navigation
- state-driven flight systems
- embedded sensor fusion

**Tech:** Embedded C, PID Control, GPS Systems, Flight Control, Embedded Systems

---

# MAGLEV GLOBE

A magnetically levitating, Bluetooth-controlled interactive globe built using custom embedded hardware, geolocation mapping, and rotational control systems.

The globe levitates through magnetic dipole pairing while a hidden continuous-rotation servo controls orientation. Since continuous servos do not provide positional feedback, the project reconstructs geographic positioning through RPM timing and calibration logic using custom rotational sensing.

The globe integrates:
- magnetic levitation
- RGB synchronization
- Flutter-based Bluetooth control
- geographic coordinate mapping
- custom embedded firmware
- timing-based servo positioning

Selecting a country in the app rotates the globe to the corresponding geographic position while synchronizing RGB lighting to the country's flag colors.

The project combines mechanical design, embedded systems, interaction design, and computational geometry into a unified physical computing system.

**Tech:** Arduino, Flutter, Bluetooth, Embedded Systems, Servo Control, Magnetic Levitation

---

# VARZONE

A real-time multiplayer debate arena built around structured argument systems, role-based participation, and live synchronization.

Varzone combines:
- debate systems
- multiplayer interaction
- AI-assisted judging
- gamified participation
- real-time communication
- state-driven progression systems

Each debate acts as a structured "arena" where users participate as:
- orators
- judges
- spectators
- AI moderators

The platform includes strict debate-state transitions, faction systems, live scoring, and optional AI-based evaluation logic.

The project explores how competitive intellectual discussion can be transformed into a real-time interactive system.

**Tech:** React, Firebase, Real-Time Systems, AI Integration

---

# SONARIUM *(In Progress)*

An experimental emotional audio engine that maps spatial movement into dynamically layered musical states to generate continuous emotional spectra.

Instead of selecting predefined songs or moods, Sonarium treats emotional states as navigable coordinate space. Mouse movement dynamically blends layered audio systems to create continuously evolving emotional soundscapes.

The project explores:
- procedural emotional synthesis
- interactive mood control
- spatial-audio mapping
- emergent musical systems
- affective computational interfaces

The goal is to create a system where users navigate emotional states rather than selecting discrete tracks.

**Tech:** JavaScript, Procedural Audio, Interactive Systems, Sound Design

---

# NANOWATCH

An open-source embedded smartwatch platform built around the Arduino Nano BLE ecosystem.

The watch integrates:
- BLE communication
- calculator systems
- custom UI modes
- low-power management
- programmable interaction logic
- hardware state management

The system uses a TM1637 display, physical button interfaces, custom firmware architecture, and BLE communication for interaction with external devices.

The project explores compact embedded system design and wearable hardware engineering.

**Tech:** Arduino, BLE, Embedded Systems, Hardware Design

---

# WASHWARE

Custom firmware for a fully programmable washing machine motherboard.

The system controls:
- motor systems
- water valves
- rinse cycles
- wash states
- safety interlocks
- timing systems
- hardware feedback logic

The firmware is structured around finite-state-machine based control systems with configurable washing behavior and embedded hardware safety constraints.

The project explores appliance control systems and embedded automation architecture.

**Tech:** Embedded C++, FSM Architecture, Hardware Control Systems

---

# CUSTOM CANVAS

A deliberately unconventional rendering engine that recreates Processing.js-style graphics entirely using dynamically generated HTML divs and CSS instead of the `<canvas>` API.

Every graphical primitive is represented as positioned DOM elements updated in real time through JavaScript.

The project explores:
- rendering systems from first principles
- spatial composition
- browser rendering behavior
- DOM-based graphics pipelines
- abstraction reconstruction

The goal was less about efficiency and more about understanding what fundamentally constitutes a rendering system beneath existing graphics abstractions.

**Tech:** HTML, CSS, JavaScript, DOM Rendering Systems

---

# MATRIX

A Processing.js experiment exploring artificial depth perception entirely within 2D space.

The simulation creates the illusion of 3D environments using:
- perspective scaling
- motion parallax
- randomized spatial motion
- depth-speed relationships
- size-distance mapping

Objects closer to the viewer move faster and appear larger while distant objects move slower and appear smaller, generating convincing depth perception without actual 3D rendering.

The project explores how spatial perception emerges from motion relationships and perspective behavior.

**Tech:** JavaScript, Processing.js, Motion Simulation, Spatial Rendering

---

# NOWYOUSEEME

A science-gallery installation demonstrating observer effect and probabilistic collapse through physical interaction.

The installation uses rotating mirrors that continuously move until a user observes the system. Upon observation:
- motion stops
- one random mirror faces the user
- uncertainty collapses into a resolved state

The project physically represents concepts related to:
- observer effect
- probabilistic collapse
- unresolved systems
- state resolution through observation

It acts as a conceptual bridge between physics-inspired philosophy and interactive installation design.

**Tech:** Physical Computing, Interactive Systems, Conceptual Installation Design

---

# AUTOPOST

An AI-assisted social automation system designed to generate and post content using randomized timing and behavioral variation.

The system integrates:
- AI-generated content
- public APIs
- randomized scheduling
- behavioral timing logic
- automated posting pipelines

The goal was to explore automated personal branding systems that mimic non-deterministic human posting behavior.

**Tech:** Python, APIs, Automation Systems, AI Integration

---

# TARSX

The official VSCode extension for the TARS programming language ecosystem.

The extension provides tooling support for TARS development and acts as the foundation for future language tooling systems including:
- syntax support
- parsing systems
- diagnostics
- semantic analysis
- language tooling infrastructure

The project exists as part of the larger TARS ecosystem.

**Tech:** VSCode Extensions, JavaScript, Language Tooling

---

# SMARTLIGHT

A dual-state ambient RGB lighting system that dynamically reacts to screen state and environmental conditions.

The system integrates:
- RGB lighting control
- embedded hardware logic
- wireless communication
- environmental synchronization
- dynamic ambient response

The project explores intelligent ambient environments and adaptive lighting systems.

**Tech:** Python, Embedded Systems, RGB Control

---

# COSMIC CIRCUITS

The official website built for Blueprint, a Bengaluru-based hardware hackathon.

The project focused on:
- branding systems
- responsive web design
- event presentation
- visual communication
- frontend interaction systems

Built as a clean, hardware-oriented digital identity for the event.

**Tech:** HTML, CSS, JavaScript, UI Design

---

# SUDOKU ALGORITHM

A JavaScript-first Sudoku solving engine focused on logical deduction through iterative possibility reduction instead of brute-force guessing.

The solver works by continuously calculating the All Possible Values (APV) for every unsolved cell by analyzing:
- rows
- columns
- 3×3 groups

As constraints propagate through the board, the algorithm refines possibilities until deterministic solutions emerge naturally.

Key features:
- interactive Sudoku solving
- APV visualization
- real-time logical deduction
- custom puzzle input
- iterative constraint propagation
- educational solving visualization

The project was built to explore algorithmic deduction systems and make the internal reasoning of Sudoku solving visually understandable rather than opaque.

**Tech:** JavaScript, Constraint Solving, DSA, Algorithm Design, Interactive Visualization

---

# Projects that were created through agent-assisted development:

## WORMHOLE

An encrypted ephemeral communication platform focused on frictionless temporary interaction and disposable communication spaces.

The system experimented with:
- anonymous room systems
- temporary encrypted messaging
- transient communication infrastructure
- lightweight realtime interaction

Built as an exploration into low-friction communication systems and ephemeral digital presence.

**Tech:** JavaScript, Firebase, Realtime Communication Systems

---

## BRICK

An experimental project exploring rapid system generation, and native notification scheduling and customization through assisted development workflows.
> This project was intended to benchmark programming capabilities of various LLMs at the time of creation.
Conclusion: 
- Well refined, UI, and interaction design
- Poorly working notification services
- Inaccurate documention and usage of Flutter

**Tech:** AI-Assisted Development, Rapid Prototyping, Experimental Systems

---

## SPOTIFY DASHBOARD

A backend-focused analytics system integrating with the Spotify API to collect, analyze, and visualize music trend data.
> This project was intended to benchmark programming capabilities of various LLMs at the time of creation.
The project explored:
- API orchestration
- music trend analysis
- realtime data handling
- backend processing systems
- structured media analytics
Conclusion:
- Sub-optimal UI and UX design
- Accurate and working API and backend design

**Tech:** JavaScript, APIs, Backend Systems, Data Analysis
