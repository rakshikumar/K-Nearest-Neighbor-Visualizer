# K-Nearest Neighbors Visualizer

An **interactive visualization** of the **K-Nearest Neighbors (KNN) algorithm** built with **Python and Pygame**.  
Move your mouse across the screen and watch how KNN classifies your point as **Red 🔴** or **Green 🟢** based on its nearest neighbors.  

---

## Features
- **Interactive classification** — move your mouse to see real-time predictions  
- **Add points dynamically** — click to add new classified points to the dataset  
- **K-value adjustable** (default: `K = 5`)  
- Great for **learning & teaching ML concepts** in a fun way  

---


## How It Works
- Generates two classes of random points:
  - **Red team (label = 0)**
  - **Green team (label = 1)**
- Uses **Euclidean distance** to calculate closeness.  
- Classifies new points based on the **majority vote** among the `K` nearest neighbors.  
- You can **add new classified points** by clicking anywhere on the screen.  

---

