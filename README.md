# Wiener Process Simulation

## Overview
This project simulates a Wiener Process, also known as Brownian motion, using Python and interactive widgets within a Jupyter Notebook environment. It allows for the dynamic visualization of the stochastic process with adjustable parameters.

## Features
- Interactive sliders to adjust the number of steps (`n_steps`), time step (`dt`), drift coefficient (`mu`), and volatility coefficient (`sigma`) of the Wiener process.
- A "Run Simulation" button to re-run the simulation after adjusting the parameters.
- Real-time updating of the simulation graph.

## Prerequisites
Make sure you have the following Python libraries installed before running the simulation:
- `numpy`
- `matplotlib`
- `ipywidgets`

## Usage
To use the simulation:
1. Adjust the parameters using the provided sliders.
2. Click the "Run Simulation" button to see the effects of the parameters on the Wiener process.
3. The plot will update in real-time to display the simulated Brownian motion.

## Code Structure
- `simulate_wiener_process`: Function to simulate the Wiener process with the given parameters.
- `plot_wiener_process`: Function to plot the simulated Wiener process.
- `update_plot`: Callback function connected to the "Run Simulation" button, which updates the plot.
- Interactive widgets: Sliders and button for controlling the simulation parameters and running the simulation.

## Contributing
Feel free to fork the project, submit pull requests, or send suggestions to improve the simulation or add new features.

## License
This project is open source and available under the MIT License.
