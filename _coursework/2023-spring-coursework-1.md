---
title: "Real Time 3D Visualization"
collection: coursework
type: "graduate course"
permalink: /coursework/2023-spring-coursework-1
venue: "Jean Monnet University"
date: 2023-01-01
location: "Lyon, France"
---

This repository contains the results of practical works for the Real Time 3D Visualization class in Jean Monnet University, lectured by Professor Philippe Colantoni. 
The first aim of this course is to understand the modern GPU architectures and capabilities. The second is
to understand and apply the basic and advanced techniques of real-time 3D rendering in the context of XR.
A focus will be placed on the web technologies (WebGL, WebVR and WebXR) that will be used to
implement these techniques. 

| Path | Description
| :--- | :----------
| [Primitives](https://shani1610.github.io/real-time-3d-visualization/primitives/) | Practical Work 1: Tasks 1 + 2
| [Custom Geometry](https://shani1610.github.io/real-time-3d-visualization/custom_geometry/) | Practical Work 1: Task 3
| [Cubeman](https://shani1610.github.io/real-time-3d-visualization/cubeman/) | Practical Work 1: Tasks 4 + 5
| [Cornell Box](https://shani1610.github.io/real-time-3d-visualization/cornell_box/) | Practical Work 2
| [Color Cloud](https://shani1610.github.io/real-time-3d-visualization/color_cloud/) | Practical Work 3: Sprint project

### Practical Work 1: Tasks 1 + 2 Primitives, Cameras and Controls

in the first task we were asked to create a scene that contains on the same plane (XY) all the primitives available in three.js. next, reproduce these primitives 3 times on the Z axis by modifying at least one parameter of their geometry. next, write a function allowing to create marks (cross based on segments) on the ground of a 3D environment that fade away as it goes far from the primitives. 
in the second task we were asked in the same web page, display the previous scene twice: one scene with an orthographic camera and second one with a perspective camera. next, use the different control techniques available in three.js to interact with these 2 types of cameras.

![primitives](https://user-images.githubusercontent.com/56839113/214873899-531df0bd-63ea-428a-918d-93bec0200de8.png)

### Practical Work 1: Task 3 Custom Geometry and Texture coordinates

for the third task we were asked to consider the 3D scene with 3 boxes in a given file and make a square hole on each face of these box. For this we must modify the geometry structure of each face in the custom geometry object, faces which are now defined as a set of 4 rectangles (which correspond to 8 triangles) instead of one initially used (which was corresponding to 2 triangles). To keep the textures correctly mapped we also must assign correct values to the texture coordinates associated to each vertex.

<img src="https://user-images.githubusercontent.com/56839113/215136592-faf6a4ab-981f-4ff8-bc4b-856f83a4bada.png" width="500">

### Practical Work 1: Task 4 + 5 Hierarchical transformations and VR experimentation

for the third task we were asked to build a scene allowing to simulate in 3D the movements of [Cubeman](https://sketchfab.com/3d-models/cubeman-a982359704c04eb59ac34a4042984f77).
Your 3D model must be identical, and it must be able to move with the same degrees of freedom. Animate this model and transform the scene in a VR experience.

<img src="https://user-images.githubusercontent.com/56839113/215136655-7bc8500b-05f2-4c64-a249-a430756fce0f.png" width="500">

### Acknowledgements

parts of the code borrowed from code given in class and from three.js documantation. 






