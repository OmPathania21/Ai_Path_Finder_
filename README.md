# 🧠 PathMind: AI Pathfinding Visualizer

**PathMind** is an interactive laboratory for exploring how artificial intelligence "thinks" about space and navigation. By transforming abstract pathfinding algorithms into high-speed visual animations, PathMind makes it possible to see the invisible trade-offs between speed, memory, and accuracy.

Visualize algorithm behavior across multiple game modes—from classic maze solving with Pacman to multi-agent pursuit scenarios with Zombie hunts, terrain analysis, and strategic radar chases.

![PathMind Demo](https://ai-path-finder-zeta.vercel.app/)

## ✨ Core Features

### 🔍 Search Algorithms
- **Breadth-First Search (BFS)**: Guarantees shortest path in unweighted grids.
- **Depth-First Search (DFS)**: Deep exploration, memory efficient but non-optimal.
- **Uniform Cost Search (UCS)**: Expansion-based Dijkstra alternative for weighted costs.
- **A* Search**: Optimized informed search using Manhattan heuristics.
- **Greedy Best-First**: Fast heuristic-only search focused on speed over optimality.
- **Depth-Limited Search (DLS)**: DFS with a hard depth cutoff.

### 🎮 Interactive Game Modes
- **Maze** (index): Classic grid-based pathfinding with interactive wall painting.
- **Pacman**: Chase scenario with AI agent pursuit.
- **Zombie**: Multi-agent survival—escape from hostile entities.
- **Dungeon**: Underground labyrinth exploration with complex corridors.
- **Terrain**: Cost-weighted pathfinding across varied terrain types.
- **Fox Chase**: Strategic predator-prey dynamics with AI opponent.
- **Radar**: Real-time tracking and navigation with sensor feedback.

### 🎨 Premium Visuals
- **Brutalist Design System**: Clean, high-contrast UI with Light and Dark mode support.
- **Gradient Path Tracing**: Final paths highlighted with dynamic color gradient (Green → Amber → Red).
- **Interactive Wall Painting**: Click and drag to draw walls or erase them.
- **Animated Generation**: Walls and passages burst into existence with smooth CSS transitions.

### 📊 Real-Time Analytics
- **Coverage Chart**: Visual bar charts showing grid exploration percentage.
- **Path Efficiency**: Measures search targeting vs. wasted node exploration.
- **Live Stats**: Node count, path length, and execution time (ms) tracking.

---

## 🛠️ Technology Stack

- **Backend**: Python / Flask (Algorithm logic & solving API)
- **Frontend**: Vanilla HTML5, CSS3, & Modern JavaScript (ES6+)
- **Styling**: Pure CSS with Custom Properties (Variables)
- **Deployment**: Configured for Vercel (JSON included)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- `pip` (Python package manager)

### Installation & Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/OmPathania21/Ai-Patha-Finder.git
   cd Ai-Patha-Finder
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the server**:
   ```bash
   python app.py
   ```

4. **Open in Browser**:
   Navigate to `http://127.0.0.1:5002`

---

## 📂 Project Structure

```text
├── app.py              # Flask server and search algorithm logic (6 algorithms)
├── Templates/          # Frontend game mode UIs
│   ├── index.html      # Main maze solver interface
│   ├── pacman.html     # Pacman chase mode
│   ├── zombie.html     # Zombie survival mode
│   ├── dungeon.html    # Dungeon exploration
│   ├── terrain.html    # Terrain pathfinding
│   ├── foxchase.html   # Fox chase game
│   └── radar.html      # Radar tracking mode
├── requirements.txt    # Python dependencies (Flask 3.0.0)
├── vercel.json         # Vercel deployment configuration (Python runtime)
└── README.md           # You are here
```

---

## ⚖️ License
Distributed under the MIT License. See `LICENSE` for more information.

Developed with ❤️ by Om Pathania.
