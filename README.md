# Planets Project: Celestial Mechanics & Orbital Modeling

Physical analysis and numerical simulations of planetary motion, apparent trajectories, eclipses, and interplanetary transfers using **SageMath** and **Python**.

**Authors:** Walid Bouzid, Sacha Donato, Simon Corvoysier

---

## Repository Structure

* **`Theoretical_Part.pdf`**: Mathematical derivations and physical study of a two-planet system with a satellite (circular orbits, collinearity/alignment conditions, changes of reference frames, epicycles, and eclipse periodicity).
* **`Partie_2_2d.ipynb`**:
  * **2D Circular Model**: Animations of the inner Solar System (Mercury, Venus, Earth + Moon, Mars + Deimos) in both **heliocentric** and **geocentric** reference frames, highlighting apparent epicyclic trajectories.
  * **2D Elliptical Model**: Accurate orbital plotting using semi-major axes and perihelion distances.
* **`Partie_2_3d.ipynb`**:
  * **3D Inclined Ellipses**: Full 3D simulation of the 4 planets of the Solar System and the Moon taking orbital inclinations into account.
  * **Probe Launch Simulation**: 3D circular model simulating a rocket/probe transfer from Earth to Mars orbit. The simulation isn't in the gif.

---

## Requirements & Usage

The notebooks require **Python 3** with a **SageMath** kernel (tested on SageMath 10.4).

1. Clone the repository:
   ```bash
   git clone https://github.com/Mieow-ai/Planet-Project.git
