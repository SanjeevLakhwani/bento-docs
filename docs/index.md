# The Surprising Mathematics of Spirograph Patterns

Spirographs are mesmerizing geometric drawings created by rolling a circle inside or outside another circle. What looks like simple doodling is actually a dance of circles governed by elegant mathematics.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Parametric Equations](#parametric-equations)
3. [How to Build Your Own](#how-to-build-your-own)
4. [Visual Examples](#visual-examples)
5. [Applications & Fun Facts](#applications--fun-facts)
6. [Conclusion](#conclusion)

---

## Introduction

A _spirograph_ pattern is generated when a smaller circle of radius \( r \) rolls around (hypotrochoid) or inside (epitrochoid) a larger fixed circle of radius \( R \). The pen point is offset by a distance \( d \) from the center of the rolling circle.

---

## Parametric Equations

- **Hypotrochoid** (rolling inside the big circle):
  \[
  \begin{cases}
  x(\theta) = (R - r)\cos\theta + d \cos\!\bigl(\tfrac{R - r}{r}\,\theta\bigr) \\
  y(\theta) = (R - r)\sin\theta - d \sin\!\bigl(\tfrac{R - r}{r}\,\theta\bigr)
  \end{cases}
  \]

- **Epitrochoid** (rolling outside the big circle):
  \[
  \begin{cases}
  x(\theta) = (R + r)\cos\theta - d \cos\!\bigl(\tfrac{R + r}{r}\,\theta\bigr) \\
  y(\theta) = (R + r)\sin\theta - d \sin\!\bigl(\tfrac{R + r}{r}\,\theta\bigr)
  \end{cases}
  \]

Where:

- \( \theta \) is the rolling angle (in radians).
- \( R \) = radius of the fixed circle.
- \( r \) = radius of the rolling circle.
- \( d \) = distance from the rolling circle’s center to the drawing point.

---

## How to Build Your Own

1. **Gather Materials**

   - Two round gears or circles (e.g., plastic wheels or cardboard cutouts)
   - A thin pen or marker
   - Cardstock paper

2. **Drill Holes**

   - In the smaller circle, drill evenly spaced holes at different radii (\( d \)).
   - One hole in the larger circle to act as a pivot.

3. **Assembly**
   - Pin the larger circle to the paper’s center.
   - Place the smaller circle inside or outside, insert the pen in one of the holes.
   - Rotate the small circle around the big one, keeping the pen pressed lightly to trace the curve.

---

## Visual Examples

- **Classic Spirograph**: \( R = 10, r = 3, d = 5 \)
- **Starburst Pattern**: \( R = 12, r = 4, d = 1 \)
- **Flower Motif**: \( R = 8, r = 2, d = 6 \)

> _Pro tip:_ Adjusting the ratio \( \tfrac{R}{r} \) to a simple fraction (e.g., \( \tfrac{5}{2}, \tfrac{8}{3} \)) yields neat, repeatable petals.

---

## Applications & Fun Facts

- **Art & Design**: Modern artists use digital spirograph generators for logos, backgrounds, and textiles.
- **Education**: Demonstrates parametric equations and harmonic motion in math classes.
- **Spirals in Nature**: Similar curves appear in shells, flowers, and planetary orbits.
- **DIY Toys**: The original Spirograph toy was patented in 1965 and remains popular today.

---

## Conclusion

Spirographs blend art with mathematics, turning simple machinery into intricate, hypnotic designs. Next time you doodle, remember the hidden geometry powering every swirl and petal!
