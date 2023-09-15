# Vehicle-Routing-Quantum

## General Information

Instituto Tecnologico de Estudios Superiores de Monterrey, campus Queretaro

TC2005S.1 - Computacion Cuantica para Todos

Friday 15, September 2023


### Participants

| Name                                 | ID        |
|--------------------------------------|-----------|
| Diego Ernesto Sandoval Vargas        | A01709113 |
| Sergio Garnica González              | A01704025 |
| Ricardo Adolfo Fernández Alvarado    | A01704813 |
| Carlos Rodrigo Salguero Alcántara    | A00833341 |

## Description

Utilizing Qiskit, Jupyter Notebook, and Python, we have crafted a solution for the Vehicle Routing Problem (VRP). Our approach involves leveraging the IBM Quantum Computing Platform, specifically harnessing the power of IBM Quantum Jobs. Through these tools, we've programmed and established connections with both quantum computer simulators and actual quantum machines to validate and verify our code's effectiveness.

## Challenge 

A delivery company has a fleet of trucks and a set of customers in different locations to deliver packages.

### Objectives

Find the shortest total trip length for all trucks to minimize total cost / time.

### Restrictions

- It is up to the team to decide on a set of locations and the scale of those locations (e.g., intercity, intra-city, last mile).
- It is up to your team to decide how many trucks are in the fleet
- Preference will be given to teams that design plans to serve the most locations, in the shortest amount of time, with the fewest number of trucks.

## Dependencies

- [qiskit](https://qiskit.org/) (version 0.44.1) - IBM's Quantum Computing Framework
- [qiskit_ibm_provider](https://qiskit.org/documentation/apidoc/ibm_provider.html) - IBM's Quantum Computing Provider for Qiskit 
- [qiskit.visualization](https://qiskit.org/documentation/apidoc/visualization.html) - Qiskit's Visualization Tools for Quantum Circuits
- [networkx](https://networkx.org/) - (version 3.1) Graph Theory Library
- [numpy](https://numpy.org/) - (version 1.25) Numerical Python Library
- [matplotlib](https://matplotlib.org/) - (version 3.8.0) Python Plotting Library
- Python 3.10.0
- Jupyter Notebook 6.4.0

## Solution

### Graph Representation

The initial graph for the problem is represented as a complete graph, where each node represents a city and edges represent the distance between two cities. 

![Initial Graph](Screenshot%202023-09-15%20113819.png)

### Graph Solution

The solution is shown as an optimize graph, where the edges represent the shortest path between two cities. Each color represents the path a truck takes for the whole fleet to deliver the packages. 

![Optimized Graph]()
