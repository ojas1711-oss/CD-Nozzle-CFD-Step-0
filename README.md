# CFD Investigation of Compressible Flow Through a Converging-Diverging Nozzle
# CFD Investigation of Compressible Flow Through a Converging-Diverging Nozzle

## Project Overview

This project investigates compressible airflow through a two-dimensional axisymmetric converging-diverging nozzle using ANSYS Fluent.

The objective was to develop a complete CFD workflow covering geometry creation, mesh generation, solver setup, convergence assessment, post-processing, and engineering interpretation of nozzle flow behavior.

The study focused on near-choking operating conditions and examined the evolution of pressure, velocity, and Mach number throughout the nozzle.

---

## Objectives

* Develop a 2D axisymmetric nozzle geometry
* Generate a high-quality quad-dominant mesh
* Simulate compressible flow using ANSYS Fluent
* Examine pressure, velocity, and Mach number distributions
* Extract centerline flow data
* Interpret nozzle behavior using compressible flow theory
* Create portfolio-quality engineering documentation

---

## Geometry

Key dimensions:

| Parameter     | Value  |
| ------------- | ------ |
| Inlet Radius  | 20 mm  |
| Throat Radius | 10 mm  |
| Outlet Radius | 20 mm  |
| Total Length  | 120 mm |

---

## Simulation Setup

| Parameter               | Value           |
| ----------------------- | --------------- |
| Solver                  | ANSYS Fluent    |
| Model                   | 2D Axisymmetric |
| Flow Type               | Compressible    |
| Fluid                   | Air             |
| Inlet Total Pressure    | 180 kPa         |
| Inlet Total Temperature | 300 K           |
| Outlet Pressure         | 101325 Pa       |

---

## Mesh Information

* Quad-dominant structured/unstructured hybrid mesh
* Local refinement near throat region
* Approximate cell count: 10,000 cells
* Mesh quality assessment performed

---

## Key Results

| Quantity                | Value    |
| ----------------------- | -------- |
| Maximum Velocity        | 306 m/s  |
| Maximum Mach Number     | 0.963    |
| Minimum Static Pressure | 91.9 kPa |

Observed behavior:

* Flow accelerates through the converging section
* Maximum velocity occurs near the throat
* Static pressure decreases as velocity increases
* Near-choking conditions are achieved
* Pressure recovery occurs in the diverging section

---

## Repository Contents

```text
reports/
    Executive Summary
    Full Technical Report

images/
    Geometry
    Mesh
    Contours
    Centerline Results
```

## Skills Demonstrated

* ANSYS Fluent
* CFD Pre-processing
* Mesh Generation
* Compressible Flow
* Post-processing
* Engineering Documentation
* Data Interpretation
* Aerospace Propulsion Fundamentals

## Author

Ojas Kiran Pohekar

Integrated B.Tech + M.Tech Aerospace Engineering

Pune, India
