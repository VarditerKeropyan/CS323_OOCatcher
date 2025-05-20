# Body Movement Visualization Project

## Overview

This project demonstrates a simple animated stick figure character performing realistic motion, including walking, hand articulation with fingers, and throwing a snowball.

The project is split into two main parts:

---

## 1. Coordinate Extraction (C++)

- Implemented in a C++ project called **BodyLinesClean**
- This component simulates and calculates body joint positions and movement frames
- Each frame contains joint coordinates and segment connections representing a human-like figure
- The coordinates are exported to a structured **JSON file**, representing a time sequence of body positions

---

## 2. Visualization (Python + Jupyter Notebook)

- Using **Jupyter Notebook** in **Visual Studio Code**
- The exported JSON is read and visualized using **Matplotlib** animations
- A Python script reads the frames and dynamically renders the stick figure
- Movement includes:
  - Walking across the canvas
  - Realistic arm movement
  - Hands with 5 fingers each
  - Interaction with a snowball (grabbing and throwing)

---

## Files

- `BodyLinesClean/` – C++ project generating movement coordinates
- `oocatcher_data.json` – JSON file containing all movement frames
- `visualize.ipynb` – Notebook rendering the animation from the JSON

---

## Requirements

- Python 3.10+
- matplotlib
- Jupyter extension for VS Code

---

## How to Run

1. Open `visualize.ipynb` in VS Code with Jupyter enabled
2. Run all cells to see the animated stick figure
3. Modify the JSON to simulate new movement patterns

---

## Author

Varditer Keropyan
