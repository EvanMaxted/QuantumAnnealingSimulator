# QuantumAnnealingSimulator
Made for the Winter 2025 offering of COMP 5114 - Quantum Communications and Networking at Carleton University taught by Michel Barbeau. 

Written by Evan Maxted

The goal of this project was to evaluate quantum annealing as an approach for solving the NP-hard optimization travelling salesman problem. At the time of this project, quantum libraries such as qiskit and pyquil did not have enough memory to properly handle the amount of qubits required for solving the TSP.

This implementation uses the OpenJij SQASampler which performs simulated quantum annealing by using a Monte Carlo sweep. I found that the simulator showed very poor performance in solving the TSP, as it produces invalid paths and unbounded path costs.

There is reason to believe that true quantum hardware will produce better results.

The documentation for OpenJij along with a link to their GitHub can all be found at their website:
https://www.openjij.org/
