# Calculus III – MATLAB Project 1

## Project Overview
This repository contains symbolic and graphical MATLAB scripts for **Calculus III Project 1**.  
The purpose of this project is to apply multivariable calculus concepts—partial derivatives, Lagrange multipliers, and triple integrals—using MATLAB’s symbolic math and 3D visualization tools.

---

## Contents

| File | Description |
|------|-------------|
| `MATLABCodeCalcIII.pdf` | Main MATLAB script containing Problems 1–5 |
| `FinalProject1.pdf` | Project instructions and grading rubric (provided by instructor) |
| `CalcIIIMatlabProject.docx` | File with documented problems and code |
| `README.md` | Project overview and documentation (this file) |

---

## Problem Summary

### Problem 1 – Plane Relationships
Use **dot** and **cross** products to determine whether pairs of planes are parallel, perpendicular, or neither.  
Normal vectors are extracted directly from the plane equations.

---

### Problem 2 – Partial Derivatives
Define  
\[
z = 7y^3 e^{3xy^2} + x^3y
\]

Compute the following symbolically using `diff`:  
\[
z_x, \; z_y, \; z_{yyx}, \; z_{xxy}, \; z_{yyxyx}
\]

---

### Problem 3 – Lagrange Multipliers
Minimize  
\[
f(x, y, z) = xy + 2xz + 2yz
\]  
subject to  
\[
xyz = 4000 \cdot 7^3
\]

Use MATLAB’s `solve` to find critical points.  
The real minimum occurs at:  
\[
(x, y, z) = (140, 140, 70), \quad f = 58{,}800
\]

---

### Problem 4 – Surfaces and Intersection
Plot the following:

- Paraboloid: \( z = 49 - 9x^2 - 9y^2 \)  
- Cylinder: \( x^2 + y^2 = \frac{49}{3} \)

Plot their intersection curve using `ezsurf` and `ezplot3`.

---

### Problem 5 – Volume of a Region
Find the volume inside the cylinder \( r = 7 \) and below the cone \( z = 14 - r \).  
Evaluate in polar coordinates:
\[
V = \int_{0}^{2\pi} \int_{0}^{7} (14 - r)r \,dr\,d\theta = \frac{1372}{3}\pi \approx 1436.755
\]

Plot the cone and cylinder surfaces to visualize the region.

---

## MATLAB Commands Used
Only commands from the **Matlab for Calculus III** handout are permitted.

| Category | Commands |
|-----------|-----------|
| Symbolic math | `syms`, `diff`, `solve`, `int` |
| Algebra & vectors | `dot`, `cross`, `subs`, `simplify` |
| 3-D graphics | `ezsurf`, `ezplot3`, `hold on`, `axis equal` |
| Display & workspace | `disp`, `clc`, `clear`, `close all` |

---

## How to Run

1. Open **Project1.m** in MATLAB.  
2. Press **Run**.  
3. For each problem section:
   - Results are displayed in the **Command Window**.  
   - 3-D plots open in separate figure windows.  
4. Copy numerical results and screenshots into the project report.

---

## Report Guidelines

| Section | Required Content |
|----------|------------------|
| Title Page | Project title, student name, date |
| Problems 1–5 | Each MATLAB output and graph clearly labeled |
| Hand Calculations | Include where required (e.g., Problems 3 & 5) |
| Discussion | Short explanation of results and geometric interpretation |

---

## Submission Instructions

Push the following to your GitHub repository:
- `Project1.m`
- `README.md`
- Screenshots (optional, in a `/figures/` folder)

Submit your GitHub repository link according to the course submission procedure.

---

## Notes
- Only commands listed in the instructor’s MATLAB handout are allowed.  
- Ignore complex (“i”) solutions; use the first real solution.  
- Check by hand whether the critical point in Problem 3 is a minimum or maximum.  
- Round numerical results only where appropriate (e.g., \( V \approx 1436.755 \)).

---

**Author:** Ihor Holubets  
**Course:** Calculus III  
**Instructor:** Lia Vas  
**Date:** [Insert submission date]
