# Automatic Braking System Project with Fuzzy Logic

![ABS Diagram](abs_diagram.gif)

## Description
This project implements an automatic braking system using fuzzy logic. It takes vehicle speed and distance to an obstacle as inputs, applies a set of fuzzy rules, and computes the required braking pressure.

## Features
- Define fuzzy membership functions for **distance** and **speed**.
- Establish a set of fuzzy rules to determine braking pressure.
- Compute braking pressure and adjusted vehicle speed.
- Visualize fuzzy sets and output using `skfuzzy`.

## Requirements
- Python 3.6+
- numpy
- scikit-fuzzy
- matplotlib (optional, for visualization)

Install dependencies with:
```bash
pip install numpy scikit-fuzzy matplotlib
```

## Usage
1. Place `automatic_braking_system_project_with_fuzzy_logic.py` and `abs_diagram.gif` in the same directory.
2. Run the script:
   ```bash
   python automatic_braking_system_project_with_fuzzy_logic.py
   ```
3. Enter the vehicle speed (0–100 km/h) and distance to obstacle (meters) when prompted.
4. View the computed braking pressure (%) and new speed value. A plot of the fuzzy output will be displayed.

## Project Structure
```
.
├── automatic_braking_system_project_with_fuzzy_logic.py
├── abs_diagram.gif
└── README.md
```

## Author
Idris Ibrahim Erten

## License
This project is licensed under the MIT License.
