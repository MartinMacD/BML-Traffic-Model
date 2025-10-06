# Biham-Middleton-Levine (BML) Traffic Model Simulation

This is a configurable python simulation of the Biham-Middleton-Levine (BML) traffic model. <br />

- East-bound cars attempt to move east, if the cell east is free then they will move east, if not possible they will stay in place. <br />
- South-bound cars attempt to move south, if the cell south is free then they will move south, if not possible they will stay in place. <br />

The grid is a torus, meaning that when cars move off the edge at one side, they reappear at the other side.

The goal of this simulation is to observe traffic patterns and visualise how traffic flow depends on car density.

## Features
- Configurable grid size
- Adjustable car density, car direction probability, and amount of simulation steps.
- Export simulation as an animated Gif.
- Track the number of cars at each step of the simulation.

## Dependencies
- NumPy
- MatplotLib
- Pillow

## Example
![BML Simulation](./bml_sim.gif)
