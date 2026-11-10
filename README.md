# 🧭 Algorithm Trace

An interactive visualiser for watching algorithms work **one operation at a time** — built as a single self-contained HTML file with zero dependencies. Double-click it, or host it anywhere; there's nothing to install.

Built as a teaching aid: the point isn't the sorted array, it's seeing *why* the array got sorted.

## ✨ What's inside

### Sorting visualiser
- **Six algorithms:** Bubble, Selection, Insertion, Merge, Quick and Heap sort.
- **Input patterns** so you can compare behaviour instead of just outcomes: random, reversed, nearly sorted, and few unique values.
- **Step mode** — advance a single comparison or swap at a time and follow the pointer movement.
- **Play mode** — run it continuously and watch the shape of the algorithm.
- **Race mode** — two sorts side by side on the same input. The fastest way to feel why O(n²) hurts.

### Pathfinding visualiser
- **Four algorithms:** BFS, DFS, Dijkstra and A*.
- **Weighted terrain** — draw **walls** (impassable) and **mud** (cost 5) so the difference between a shortest path and a *cheapest* path is visible, not theoretical.
- **Wall/erase tools** and a random **maze generator** for instant test grids.

## 🛠️ How it's built

One file: `algorithm-trace-interactive.html` — semantic markup, inline styles and vanilla JavaScript. No build step, no framework, no network calls, so it works offline and inside a classroom projector with no setup.

## ▶️ Run it

```bash
git clone https://github.com/hariomgupta2596-source/Algorithm_Trace.git
cd Algorithm_Trace
open algorithm-trace-interactive.html     # or just double-click the file
```

## 💡 What it's for

Explaining algorithm behaviour to someone who has read the pseudocode but never *seen* it. Weighted terrain was the interesting part: BFS and Dijkstra return visibly different paths once cost is unequal, which is much more persuasive than a paragraph about priority queues.
