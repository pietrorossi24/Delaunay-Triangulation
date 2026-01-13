# Delaunay Triangulation in C++

A high-performance C++ implementation for generating the **Delaunay Triangulation** from a set of discrete points in a 2D plane. This project was developed as part of the numerical analysis and computational geometry curriculum at **Politecnico di Torino**.

## 🛠 Project Overview

The Delaunay triangulation for a given set  of discrete points in a plane is a triangulation  such that no point in  is inside the circumcircle of any triangle in . This project focuses on:

* **Geometric Robustness**: Handling collinear points and precision issues.
* **Efficiency**: Optimized data structures for point location and edge flipping.
* **Visualization**: (Optional, if you used one) Exporting data for plotting via Python/Matplotlib or MATLAB.

## 🚀 Features

* **Incremental Algorithm**: Efficiently builds the triangulation by adding points one by one.
* **Edge Flipping**: Ensures the "empty circumcircle" property is maintained.
* **Custom Geometric Library**: Includes primitive tests such as `Orientation` and `InCircle` using robust predicates.
* **I/O Handling**: Supports reading point clouds from `.txt` or `.csv` files.

