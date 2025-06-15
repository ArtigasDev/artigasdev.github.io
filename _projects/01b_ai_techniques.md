---
name: AI Techniques
tools: [WIP, AI, C#, Unity]
image: https://i.imgur.com/qUBBRVI.gif
description: A project making use of various AI techniques such as Marching Cubes and the A* algorithm.
---

{% include elements/video.html id="069kz84pFZc" %}

The aim of this project is the implementation and visualisation of various AI techniques across several scenes in Unity.<br><br>

---

# Overview
Currently a 3D procedural terrain is generated using the Marching Cubes algorithm and Perlin Noise.
Two scenes have been created in which, at the press of a button, a completely random terrain will be created from scratch. Different parameters can be modified to control the appearance of the terrain.<br><br>
The first one makes use of Perlin Noise 2D, so the resulting terrain will look like mountainous surfaces.
The second, which makes use of Perlin Noise 3D, will result in terrain that looks like the inside of a cave.<br><br>
In addition, the project has a third scene in which a 2D grid of any dimensions can be created. The layout of this grid is associated with the algorithm called Cellular Automata. Once the grid is created, the user can indicate two traversable cells and then execute the A* algorithm, which will indicate the shortest path between these two cells around any type of obstacle on the way.

Since the project is still in progress, updates will be made regularly to this page to keep you informed.
<br><br>

---

# Current Features
- Marching Cubes.
- Perlin Noise 2D & 3D.
- Cellular automata.
- A*.

## Future Expected Features
- Wave Function Collapse.
- Entities using the implemented A*.
<br><br>

---

# How it was implemented
Work in progress...<br><br>

---

### Developed by: 
- Ángel Artigas Pérez 

<p class="text-center">
{% include elements/button.html link="https://artigasdev.github.io/projects/" text="Back" %}
</p>