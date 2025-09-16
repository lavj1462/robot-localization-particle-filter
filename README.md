# robot-localization-particle-filters
# Robot Localization with Particle Filters
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lavj1462/robot-localization-particle-filter/blob/main/localization.ipynb)


This project demonstrates **robot localization** using a **particle filter** implemented in Python with OpenCV.

The robot is placed on a terrain map (`map.png`) and estimates its position using:
- **Motion model**: Applies noisy forward and turn movements.
- **Sensor model**: Reads terrain elevation values from the map.
- **Particle filter**: Uses 3000 particles to represent possible robot states.
- **Resampling + noise**: Updates the particle cloud to converge around the robot’s true location.

---

## 📂 Project Files
- `localization.py` – Python implementation of the particle filter.  
- `robot_localization.ipynb` – Jupyter notebook version of the project.  
- `map.png` – Grayscale map used for terrain elevation.

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/lavj1462/robot-localization-particle-filter.git
   cd robot-localization-particle-filter
