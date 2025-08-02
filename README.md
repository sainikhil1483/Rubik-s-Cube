# 🧠 Rubik’s Cube Solver

An interactive and extensible algorithmic solver for the standard **3x3 Rubik’s Cube**, implemented with a web-based visual UI and scalable to other twisty puzzles.

## 🚀 Overview

This project models and solves the Rubik’s Cube using only valid cube moves, closely mirroring real-world solving techniques. Scramble any cube state, visualize the solution step-by-step, and learn from algorithmic strategies in real-time.

## ✨ Features

- **🎲 Full Simulator**  
  Interactive 3D UI for scrambling, solving, and exploring the cube.

- **🧠 Algorithmic Solver**  
  Finds solutions from any scrambled state using efficient, layered algorithms (twists, commutators, conjugates).

- **👁️ Visualization**  
  Step-by-step playback of each move (with move names, face highlighting, and undo/redo support).

- **📈 Scalability**  
  Supports 2x2, 3x3, 4x4 cubes and other polyhedral puzzles (Dodecahedron, Tetrahedron, etc.).

- **🧪 Custom Analysis**  
  Advanced tools to manipulate cube states, including point-and-swap to study edge cases.

- **⚡ Performance**  
  Leverages browser web workers for fast solving and smooth UI responsiveness.

## ⚙️ Technical Approach

- **Data Structures**  
  Each sticker, face, and slice of the cube is modeled as an object. Fast permutation-based updates ensure real-time responsiveness.

- **Move Engine**  
  Cube moves are applied as efficient composable permutations via cycle notation.

- **Cluster-based Solving**  
  Solution space is reduced using swappable sticker groupings and cached commutator patterns.

- **Efficient State Tracking**  
  Permutation maps and solver stacks allow for instant replay, undo/redo, and validation.

## 🧩 How to Use

1. **Open the Web UI**  
   Launch the application in your browser.

2. **Choose Cube Type**  
   Select your cube size (2x2, 3x3, 4x4) or puzzle shape (tetrahedron, dodecahedron, etc.).

3. **Scramble**  
   Scramble the cube either randomly or manually.

4. **Solve**  
   Click **"Solve"** to watch the step-by-step animation solving the puzzle using legal moves.

5. **Explore**  
   Use additional tools for:
   - Tracking move history
   - Inspecting states
   - Trying alternative solving strategies


