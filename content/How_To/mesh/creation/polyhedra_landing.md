---
title: Creating Polyhedra Shapes
image: 
description: Learn how to create polyhedra shapes in Babylon.js.
keywords: welcome, babylon.js, diving deeper, meshes, polyhedra shapes
further-reading:
video-overview:
video-content:
---

## Polyhedra
There are a multitude of polyhedra, too many to create by individual names, other than the cube which uses *CreateBox*. The names themselves often take too long to write when coding and so Babylon.js has provides 15 basic ones a number. There are many beyond  these 15 and those can be created from custom data sets provided in the form of Playground examples. 

The twenty sided icosahedron has the interesting property of approximating a sphere. By dividing each face into triangles and then mapping the resulting vertices onto a sphere it gives a better approximation of a sphere. The solids formed are called icospheres and provide a more regular distribution of triangles around a sphere then the *CreateSphere* method.