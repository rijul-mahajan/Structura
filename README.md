# Structura — Interactive DSA Visualizer

**Learn data structures and algorithms by watching them work.**

Structura is a browser-based, interactive visualizer for exploring common data structures and algorithms. Choose a topic, change the input, and step through each operation to see how the underlying data changes.

**[Open Structura](https://rijul-mahajan.github.io/Structura/)**

---

## Explore

### Data structures

| Topic | What you can explore |
|---|---|
| **Array** | Index-based access, insertion, deletion, updating, and searching |
| **Linked List** | Node connections, insertion, deletion, and traversal |
| **Stack** | Push, pop, and peek operations |
| **Queue** | Enqueue and dequeue operations |
| **Binary Search Tree** | Insertion, searching, and tree traversal |
| **Hash Table** | Hashing, buckets, and collision handling |
| **Min Heap** | Heap insertion and extracting the minimum |
| **Deque** | Adding and removing elements at either end |

### Algorithms

- **Searching:** Linear Search, Binary Search
- **Sorting:** Bubble Sort, Quicksort, Selection Sort, Insertion Sort, Merge Sort, Heap Sort, Shell Sort
- **Graph algorithms:** Breadth-First Search (BFS), Depth-First Search (DFS), Dijkstra's shortest-path algorithm

---

## How to use Structura

1. **Choose a topic** from the navigation panel. Use the search shortcut to jump directly to a data structure or algorithm.
2. **Set your input** in the data field, or try the built-in presets: Random, Sorted, Reversed, and Nearly Sorted.
3. **Choose an operation** and provide any required value, index, or starting node.
4. **Run the operation** to generate its step-by-step visualization.
5. **Explore the execution** with the playback controls:
   - Play or pause the animation.
   - Move one step forward or backward.
   - Reset the operation.
   - Drag the timeline to inspect a particular step.
   - Adjust the playback speed.
6. **Understand each step** using the explanation and execution log. The code panel shows the corresponding implementation and lets you switch between available languages.

## Features

- **Interactive visualizations** of arrays, linked lists, stacks, queues, trees, heaps, hash tables, and graphs.
- **Step-by-step execution** with playback, pause, reset, forward/backward navigation, and a scrub-able timeline.
- **Adjustable speed** so you can inspect operations at your own pace.
- **Custom inputs and presets** to experiment with different data.
- **Explanations and execution history** that describe what happens during an operation.
- **Code alongside the visualization** to connect each visual step with its implementation.
- **Keyboard shortcuts and topic search** for faster navigation.
- **Theme and sound controls** for a more configurable experience.

## Keyboard shortcuts

| Shortcut | Action |
|---|---|
| `Space` | Play / pause |
| `←` | Step backward |
| `→` | Step forward |
| `R` | Reset |
| `Ctrl + K` | Open topic search |
| `⌘ + K` | Open topic search on Mac |

## Run locally

Structura is a static web app. It does not require Node.js, a package manager, a build step, or a backend.

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.

The app can also be hosted by any static web hosting provider.

## Built with

- HTML
- CSS
- JavaScript

The interface loads Inter and JetBrains Mono from Google Fonts. System fallback fonts are used if the fonts are unavailable.

## Contributing

Suggestions, bug reports, and improvements are welcome. If you find an issue or have an idea for a new visualization, open an issue in this repository.

---

*Structura is an educational tool intended to help make the mechanics of data structures and algorithms easier to see and understand.*
