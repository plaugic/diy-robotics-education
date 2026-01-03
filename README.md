# B.S. Computer Engineering: Applied Robotics & AI Track (Shadow Curriculum)

**Institution:** University of California, San Diego (Simulated)
**Department:** Electrical & Computer Engineering (ECE)
**College:** Warren College (Optimized for Engineering)
**Total Units:** 180+
**Goal:** Hardware/Software Integration, Control Theory, & Autonomous Systems

---

## 0. Prerequisites (The "Hidden" Requirements)
*You must master these before attempting Year 1. If you fail here, you will fail Calculus.*

### Mathematics
- [ ] **Pre-Calculus & Trigonometry:** Unit circle, trig identities, logarithmic functions, exponential decay.
    - *Check:* Can you solve `sin(2x) = 1` for x without a calculator?
- [ ] **Algebra II:** System of equations, factoring quadratics, inequalities.

### Physics
- [ ] **Classical Mechanics (High School Level):** Newton's Three Laws, Kinematics equations (velocity/acceleration), Free Body Diagrams.

### Tools
- [ ] **Terminal Literacy:** Navigating folders (`cd`, `ls`), compiling code (`gcc`), and basic Bash scripting.
- [ ] **Touch Typing:** 60+ WPM. (You cannot code if you hunt-and-peck).

---

## YEAR 1: The Foundation (The "Weeder" Year)
*Objective: Survive the math and learn to speak the language of computers.*

### Fall Quarter (16 Units)
- [ ] **MATH 20A: Calculus I (Differential)**
    - *Topics:* Limits, Derivatives, Continuity, Optimization problems.
    - *Resource:* MIT 18.01 (Single Variable Calculus).
- [ ] **CSE 11: Intro to Computer Science & Object-Oriented Programming (Java)**
    - *Topics:* Classes, Objects, Inheritance, Polymorphism, Recursion.
    - *Hardcore Check:* Build a version of "Tetris" from scratch using Java Swing.
- [ ] **CHEM 6A: General Chemistry I**
    - *Topics:* Atomic theory, bonding, stoichiometry. (Required for Engineering breadth).
- [ ] **GE: Writing I (Warren Writing 10A)**
    - *Focus:* Argumentative writing.

### Winter Quarter (16 Units)
- [ ] **MATH 20B: Calculus II (Integral)**
    - *Topics:* Integration by parts, Taylor Series, Polar coordinates.
    - *Hardcore Check:* Calculate the volume of a torus (donut) using the Shell Method.
- [ ] **CSE 12: Basic Data Structures & Algorithms**
    - *Topics:* Linked Lists, Stacks, Queues, Hash Tables, Heaps in C/C++.
    - *Key Skill:* Managing memory manually (pointers/malloc).
- [ ] **CSE 15L: Software Tools & Techniques**
    - *Topics:* Debugging (GDB), Version Control (Git), Unix tools.
- [ ] **PHYS 2A: Mechanics (Calculus-Based)**
    - *Topics:* Vectors, Torque, Angular Momentum, Harmonic Motion.

### Spring Quarter (16 Units)
- [ ] **MATH 20C: Calculus III (Multivariable)**
    - *Topics:* Partial derivatives, Gradients, Double/Triple integrals.
- [ ] **CSE 30: Computer Organization & Systems Programming**
    - *Topics:* Assembly Language (ARM/x86), CPU Registers, Stack Frames, Bitwise operations.
    - *Hardcore Check:* Write a C program that manually corrupts the stack to execute a "hidden" function (Buffer Overflow).
- [ ] **PHYS 2B: Electricity & Magnetism**
    - *Topics:* Gauss's Law, Ampere's Law, Maxwell's Equations.
    - *Note:* This is the hardest lower-division class.

---

## YEAR 2: The Core Engineering (The "Filter" Year)
*Objective: Bridge the gap between hardware (circuits) and software (math).*

### Fall Quarter (16 Units)
- [ ] **MATH 20D: Differential Equations**
    - *Topics:* First/Second order ODEs, Laplace Transforms.
    - *Why:* This is the math of Robotics Control Theory.
- [ ] **ECE 35: Introduction to Analog Design**
    - *Topics:* Kirchhoff's Laws (KCL/KVL), Op-Amps, RLC Circuits.
    - *Hardcore Check:* Build an active audio filter on a breadboard that removes specific frequencies.
- [ ] **PHYS 2C: Fluids, Waves, Thermodynamics**
    - *Topics:* Entropy, Heat engines, Wave equation.

### Winter Quarter (16 Units)
- [ ] **MATH 18: Linear Algebra**
    - *Topics:* Matrix multiplication, Eigenvalues/Eigenvectors, Basis, Null space.
    - *Why:* **This is the language of Artificial Intelligence.**
- [ ] **ECE 45: Circuits & Systems**
    - *Topics:* Fourier Series, Frequency Response, Convolution, Transfer Functions.
    - *Hardcore Check:* Mathematically filter a noisy audio signal using Fourier Transforms.
- [ ] **CSE 21: Mathematics for Algorithms**
    - *Topics:* Graph Theory, Combinatorics, Logic, Probability.

### Spring Quarter (16 Units)
- [ ] **ECE 65: Components & Circuits Lab**
    - *Topics:* Transistors (MOSFETs/BJTs), Diodes, Amplifiers.
    - *Skill:* Real hardware debugging with an Oscilloscope.
- [ ] **CSE 100: Advanced Data Structures**
    - *Topics:* Red-Black Trees, AVL Trees, Tries, Graph Algorithms (Dijkstra, BFS/DFS).
    - *Hardcore Check:* Implement a "Huffman" file compressor in C++.
- [ ] **ECE 108: Digital Circuits**
    - *Topics:* Boolean Logic, Flip-Flops, Finite State Machines, Verilog HDL.

---

## YEAR 3: The Advanced Systems (The "Engineer" Year)
*Objective: Design complex systems. Master the hardware-software interface.*

### Fall Quarter (16 Units)
- [ ] **CSE 101: Design & Analysis of Algorithms**
    - *Topics:* Dynamic Programming, Greedy Algorithms, NP-Completeness.
    - *Why:* This is the class that passes Google/Netflix interviews.
- [ ] **ECE 101: Linear Systems Fundamentals**
    - *Topics:* Discrete Fourier Transform (DFT), Z-Transform, Digital Filters.
    - *Context:* Signal processing for robot sensors.
- [ ] **CSE 140: Component Design & Architecture**
    - *Topics:* CPU Datapath design, ALU design.
- [ ] **CSE 140L: Digital Systems Lab**
    - *Project:* Build a functional CPU in Verilog/SystemVerilog.

### Winter Quarter (16 Units)
- [ ] **CSE 141: Introduction to Computer Architecture**
    - *Topics:* Pipelining, Branch Prediction, Cache Coherence, Memory Hierarchy.
- [ ] **CSE 141L: Project in Computer Architecture**
    - *Project:* Design a custom Instruction Set Architecture (ISA) and simulate it.
- [ ] **CSE 120: Operating Systems**
    - *Topics:* Concurrency, Threads, Semaphores, Virtual Memory, File Systems.
    - *Hardcore Check:* Implement "malloc" from scratch.

### Spring Quarter (16 Units)
- [ ] **ECE 111: Advanced Digital Design Project**
    - *Focus:* FPGA Programming.
    - *Project:* Hardware acceleration for neural networks on an FPGA.
- [ ] **MATH 183: Statistical Methods**
    - *Topics:* Probability theory, Hypothesis testing.
- [ ] **Technical Elective 1: Robotics Foundation**
    - *Course:* **MAE 148: Intro to Autonomous Vehicles**
    - *Project:* Program a self-driving car (Jetson Nano/Raspberry Pi) to navigate a track.

---

## YEAR 4: The Specialization (The "Robotics" Year)
*Objective: Applied AI and Robotics. The Capstone.*

### Fall Quarter (16 Units)
- [ ] **ECE 174: Optimization for Machine Learning**
    - *Topics:* Convex optimization, Gradient Descent, Least Squares.
- [ ] **CSE 176A: Healthcare Robotics (Introduction to Robotics)**
    - *Topics:* Kinematics (Forward/Inverse), Jacobian, Path Planning, Haptics.
- [ ] **ECE 175A: Elements of Machine Learning I**
    - *Topics:* Pattern recognition, Bayesian learning, Gaussian Mixture Models.

### Winter Quarter (16 Units)
- [ ] **ECE 172A: Robotics & Machine Vision**
    - *Topics:* Computer Vision, 3D Reconstruction, Object Recognition for robots.
- [ ] **ECE 175B: Elements of Machine Learning II**
    - *Topics:* Neural Networks, Deep Learning, Support Vector Machines.
- [ ] **General Education: Ethics in Engineering**
    - *Context:* AI Safety and bias.

### Spring Quarter (12 Units) - GRADUATION
- [ ] **ECE 191: Engineering Group Design Project (Capstone)**
    - *The Final Boss:* A semester-long project sponsored by industry (e.g., Qualcomm/Northrop).
    - *Example:* "Autonomous Drone Swarm for Search and Rescue."
- [ ] **Technical Elective: Embedded Systems**
    - *Course:* **CSE 145: Embedded System Design**
    - *Focus:* Low-power design, Real-Time Operating Systems (RTOS).

---

## The "Self-Correction" Mechanisms
*If you are doing this solo:*

1.  **The "Syllabus Hack":** For every course listed above, search `UCSD [Course Code] Github` or `UCSD [Course Code] Syllabus`. You will find the actual homework assignments from past students.
2.  **The "Textbook" Standard:**
    * *CSE 101* = "Introduction to Algorithms" (CLRS).
    * *ECE 35/45* = "Fundamentals of Electric Circuits" (Alexander & Sadiku).
    * *CSE 30* = "Computer Systems: A Programmer's Perspective" (Bryant & O'Hallaron).
3.  **The "Portfolio" Rule:** You do not get a grade. Your "Grade" is the GitHub repository for the final project of each class.
