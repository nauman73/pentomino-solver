# 🧩 Pentomino Puzzle Solver

An interactive pentomino puzzle solver featuring a sophisticated Algorithm X + Dancing Links implementation for optimal exact cover solving.

## 🌟 Features

- **Interactive Puzzle Interface**: Drag, drop, rotate, and flip pentomino pieces
- **Advanced AI Solver**: Algorithm X with Dancing Links for optimal solving
- **Real-time Visualization**: Watch the AI solve step-by-step
- **Customizable Solving**: Adjust speed, randomization, and visualization settings
- **Seeded Randomization**: Reproducible solving with custom seeds
- **Performance Statistics**: Track attempts, backtracks, and cover operations

## 🎮 How to Play

1. **Manual Play**: 
   - Drag pieces from the right panel onto the 8×8 grid
   - Right-click pieces to rotate them
   - Double-click pieces to flip horizontally
   - Double-click placed pieces to remove them

2. **Auto Solver**:
   - Click "🚀 Start Solving" to watch the AI solve automatically
   - Adjust speed and randomization settings for different solving behaviors
   - Use seeds for reproducible solutions

## 🎯 Goal

Fit all 12 pentomino pieces into the 8×8 grid with the 2×2 center hole (60 squares total).

## 🔬 Technical Details

- **Algorithm**: Dancing Links implementation of Knuth's Algorithm X
- **Exact Cover Problem**: Each cell must be covered exactly once
- **Optimization**: Minimum remaining values heuristic with randomization
- **Performance**: Handles thousands of backtracking operations efficiently

## 🚀 Live Demo

[View Live Demo](https://yourusername.github.io/pentomino-solver/)

## 💻 Local Development

Simply open `index.html` in any modern web browser. No build process or dependencies required!

## 📊 Algorithm Performance

The solver uses advanced heuristics and can find solutions in:
- Low randomization: Usually < 10 seconds
- High randomization: Variable timing for diverse solution exploration
- Seeded solving: Reproducible results for testing and demonstration

## 🎨 UI Features

- Modern, responsive design
- Real-time progress tracking
- Comprehensive solving statistics
- Intuitive drag-and-drop interface
- Visual feedback and animations

---

Built with vanilla HTML, CSS, and JavaScript. No external dependencies required.
