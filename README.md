# 🧠 PathMind: AI Pathfinding Visualizer

**PathMind** is more than just a tool; it's an interactive laboratory for exploring how artificial intelligence "thinks" about space and navigation. By transforming abstract pathfinding algorithms into high-speed visual animations, PathMind makes it possible to see the invisible trade-offs between speed, memory, and accuracy.

Whether you're testing the surgical precision of **A*** or the brute-force curiosity of **Breadth-First Search**, PathMind provides a cinematic environment to build complex mazes, create obstacles, and watch AI find its way home.

![PathMind Demo](https://ai-patha-finder.vercel.app/)

## ✨ Core Features

### 🔍 Search Algorithms
- **Breadth-First Search (BFS)**: Guarantees shortest path in unweighted grids.
- **Depth-First Search (DFS)**: Deep exploration, memory efficient but non-optimal.
- **Uniform Cost Search (UCS)**: Expansion-based Dijkstra alternative for weighted costs.
- **A* Search**: Optimized informed search using Manhattan heuristics.
- **Greedy Best-First**: Fast heuristic-only search focused on speed over optimality.
- **Depth-Limited Search (DLS)**: DFS with a hard depth cutoff.

### 🗺️ Intelligent Maze Generation
- **Animated Carving**: Watch in real-time as the **Recursive Division** algorithm snakes through walls.
- **Random Distribution**: Burst-style generation of scattered obstacles.
- **Spiral Corridor**: Generates a long, narrow path to test algorithm efficiency.

### 🎨 Premium Visuals
- **Brutalist Design System**: A clean, high-contrast UI with Light and Dark mode support.
- **Gradient Path Tracing**: Final paths are highlighted with a dynamic color gradient (Green → Amber → Red).
- **Interactive Wall Painting**: Click and drag to draw walls or erase them.
- **Animated Generation**: Walls and passages burst into existence with smooth CSS transitions.

### 📊 Real-Time Analytics
- **Coverage Chart**: Visual bar charts showing the percentage of the grid explored.
- **Path Efficiency**: Measures how targeted the search was vs. how many nodes were wasted.
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
   Navigate to `http://127.0.0.1:5000`

---

## 📂 Project Structure

```text
├── app.py              # Flask server and search algorithm logic
├── templates/
│   └── index.html      # Main UI (CSS, HTML, JS)
├── requirements.txt    # Python dependencies
├── vercel.json         # Vercel deployment configuration
└── README.md           # You are here
```

---

## ⚖️ License
Distributed under the MIT License. See `LICENSE` for more information.

Developed with ❤️ by Om Pathania.
