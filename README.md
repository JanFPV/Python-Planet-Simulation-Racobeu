# Python Planet Simulation

This repository contains a Python-based simulation of planets orbiting around the sun using the Pygame library. The simulation models the gravitational interactions between the sun and several planets, allowing you to visualize their orbits.

## Features

- Realistic simulation of planetary orbits using Newton's law of universal gravitation.
- Visualization of the planets and their orbits.
- Ability to pause and resume the simulation using the spacebar.
- Display of planet statistics on the screen.

## Files

- `planetSim.py`: The main script that runs the planet simulation.
- `tutorial_notebook.py`: A script version intended for educational purposes.
- `planetSim.ipynb`: A Jupyter notebook version of the simulation for interactive learning.

## Requirements

- python 3.x
- pygame
- ipykernel

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/JanFPV/Python-Planet-Simulation-Racobeu.git
   cd Python-Planet-Simulation-Racobeu
   ```

2. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

To run the simulation, execute the `planetSim.py` script:
```sh
python planetSim.py
```

To interactively explore the simulation, open the `planetSim.ipynb` notebook in Jupyter:
```sh
jupyter notebook planetSim.ipynb
```

## How It Works

The simulation uses the `Planet` class to represent each planet. The class includes methods to calculate gravitational forces, update positions, and draw the planets on the screen. The main loop handles the simulation updates and rendering.

## Controls

- **Spacebar**: Pause/Resume the simulation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project was developed as part of an educational course at VUAS in Ventspils, Latvia.
