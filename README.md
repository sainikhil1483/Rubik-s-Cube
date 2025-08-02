# Rubik-s-Cube

Rubik’s Cube Solver
An interactive and extensible algorithmic solver for the standard 3x3 Rubik’s Cube—implemented with a web-based visual UI and scalable to other twisty puzzles.

🚀 Overview
This project models and solves the Rubik’s Cube using only valid cube moves, closely mirroring real-world solving techniques. Scramble any cube state, visualize the solution step-by-step, and learn from algorithmic strategies in real-time.

✨ Features
Full Simulator: Interactive 3D UI for scrambling, solving, and exploring the cube.

Algorithmic Solver: Finds solutions from any scrambled state using efficient, layered algorithms (twists, commutators, conjugates).

Visualization: Step-by-step playback of each move (with move names, highlighting, and undo/redo).

Scalability: Supports 2x2, 3x3, 4x4 cubes and other polyhedral puzzles (Dodecahedron, Tetrahedron, etc.).

Custom Analysis: Advanced tools to manipulate states, including point-and-swap to study edge cases.

Performance: Leverages browser web workers for fast solving and smooth UI responsiveness.

⚙️ Technical Approach
Data structures: Models each sticker, face, and cube slice as objects, with fast permutation-based state updates.

Move Engine: Moves are abstractions of sticker permutations, applied efficiently via composable cycles.

Cluster-based Solving: Reduces solution space using groupings of swappable stickers and cached commutator patterns.

Efficient State Tracking: Maintains permutation maps and solver stacks for instant replay, undo/redo, and state validation.

🧩 How to Use
Open the UI. Select your cube size and shape.

Scramble the cube (randomly or manually).

Click "Solve" to generate a step-by-step solution—watch the cube animate each legal move back to solved!

Use additional features for stats, alternative views, or explore generalized puzzles.
