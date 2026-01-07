# BASIC_DAILY




# A simple C++ G-code parser 

```
https://github.com/dillonhuff/gpr
```



### 📌 What kind of code it is

✔ It’s a **simple C++ G‑code parser library**.
✔ It breaks raw text from a G‑code file into usable blocks/commands.
✔ It does **not interpret meaning** of commands — just parses. 

So it’s not a full CNC driver — it’s the **first step**: reading and understanding the text format.

---

### 📌 What advantage you get from it

**GPR gives you:**

* A reusable C++ parser you can drop into your own CNC tools. 
* A foundation for **reading any G‑code file**, regardless of dialect. 
* Structured output (blocks/words/comments) instead of raw text. 

**What that means in practice:**

* You can load G‑code from disk and work with it programmatically.
* You can build your own higher‑level tools: visualizer, simulator, converter.
* You can filter or modify instructions before generating final machine commands.

---

### 📌 How you can use it effectively

Instead of directly printing parsed output, you can:

✅ Read G‑code into a data structure
✅ Loop through blocks and inspect each code (G/M/X/Y etc.)
✅ Generate your own modified version
✅ Build tools like:

* G‑code cleaner
* Optimizer (remove redundant moves)
* Visualizer
* Simulator
* Custom CNC controller backend

---

### 📌 Effect on your future projects

Learning this gives you:
**Fundamental CNC software skill** — how G‑code is processed at the lowest level.

That helps when you build:
✔ CNC tools
✔ Custom controllers
✔ CAM preprocessing
✔ Machine simulators

You learn how to turn raw G‑code text into **structured, actionable data** — a foundational building block in CNC and robotics.

---

**Bottom line:**
**GPR doesn’t do fancy CNC work yet — it just reads and structures G‑code.** But that is the **core first step** of almost every CNC/robotics software that deals with G‑code. 




###  3D Computational Geometry in C++11 


```

https://github.com/dillonhuff/scg
```



### ✅ What it is

A **C++11 geometry library** for 3D shapes:

* vectors, points
* planes
* meshes
* triangles
* transforms
* STL loading

### 🔥 What you can do with it

**Read and work with 3D models**

* Load `.stl` files
* Get all triangles and vertex data
* Inspect mesh geometry

**Modify geometry programmatically**

* Transform (rotate, scale, translate)
* Slice or cut meshes
* Compute normals, intersections
* Build new meshes

**Generate new geometry**

* Create shapes
* Combine/merge meshes
* Export modified models

### 📈 Real‑world uses

✔ 3D model processing
✔ CAM tool development
✔ Geometry algorithms
✔ Path planning
✔ Collision detection
✔ 3D printed toolpaths
✔ CNC slicing → 2D contours

### 💡 How to use it effectively

1. **Load a mesh** from STL
2. **Access points & triangles**
3. **Modify or analyze the mesh**
4. **Output results or use downstream**
   (e.g., generate toolpaths or export new mesh)

### 🎯 Key advantage

It gives you **real, usable 3D data**, not text — so you can build geometry‑aware CAD/CAM features.

---


```
 GRBL controller application with G-Code visualizer written in Qt. 
https://github.com/trasz/grblControl?utm_source=chatgpt.com



https://github.com/Denvi/Candle


https://github.com/hudbrog/gCodeViewer?utm_source=chatgpt.com

```




how to load an STL and print number of points/triangles.


