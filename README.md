# Advanced Python Class Assignment

## Repository Overview

This repository has been created as part of an assignment by Nathan Galindo for his Advanced Python class. It contains a simple Python script demonstrating basic usage of the `matplotlib` and `numpy` libraries.

### Contents

- `plot_sin_curve.py`: A Python script that generates a plot of the sine function over a specified range and prints "Hello, World!" to the console.

### Script Functionality

The script `plot_sin_curve.py` performs the following actions:

1. **Import Libraries**: 
    - `matplotlib.pyplot` for plotting graphs.
    - `numpy` for numerical operations.

2. **Generate Data Points**:
    - Creates an array `x` with 100 linearly spaced points between 0 and 20.

3. **Plotting**:
    - Plots the sine of these points using `plt.plot(x, np.sin(x))`.

4. **Display the Plot**:
    - Displays the plot with `plt.show()`.

5. **Print Statement**:
    - After displaying the plot, the script prints "Hello, World!" to the console.

### How to Run

To run this script, ensure you have Python installed along with the `matplotlib` and `numpy` libraries. You can run the script using the following command in your terminal:

```bash
python plot_sin_curve.py