# Modeling Air Pollution Using Environmental Drones

## Project Overview
This repository contains a project that models air pollution using environmental drones. Our approach leverages genetic algorithms to optimize the paths of multiple drones for efficient real-time air quality data collection in urban environments. The project includes simulations, cost analysis, and visualizations to identify and monitor air quality hotspots.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
  - [Identifying Hotspots](#identifying-hotspots)
  - [Drone Selection](#drone-selection)
  - [Genetic Algorithm for Path Optimization](#genetic-algorithm-for-path-optimization)
- [Experiments and Results](#experiments-and-results)
  - [Single-Agent Experiments](#single-agent-experiments)
  - [Multi-Agent Experiments](#multi-agent-experiments)
  - [Cost Analysis](#cost-analysis)
- [Visualization](#visualization)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

## Introduction
Air pollution poses significant health and environmental risks. Accurately measuring air pollution levels is crucial for developing solutions. This project investigates using small drones to survey air pollution in urban areas, offering a detailed and real-time air quality assessment.

## Methodology
### Identifying Hotspots
We identified potential hotspots on the Georgia Tech campus based on population density and outdoor activity areas. Locations were selected for Air Quality Index (AQI) measurements to ensure comprehensive monitoring.

### Drone Selection
Market research was conducted to select suitable drones. The chosen drones include the DJI Matrice 300, Matrice 600, and Phantom 4, each evaluated for flight time, cost, and suitability for the task.

### Genetic Algorithm for Path Optimization
The multi-agent traveling salesman problem (MATSP) was employed to optimize drone paths. A genetic algorithm was used to ensure efficient coverage of identified hotspots, minimizing total travel distance while considering drone constraints.

## Experiments and Results
### Single-Agent Experiments
Simulations with single drones showed that while some drones could complete the mission, others, like the Phantom 4, had limitations in flight time and coverage.

### Multi-Agent Experiments
Multi-agent experiments using multiple drones (e.g., Phantom 4, Matrice 600) demonstrated improved efficiency and reliability, with varied drone counts optimizing cost and coverage.

### Cost Analysis
The cost analysis revealed that using multiple Phantom 4 drones provided a cost-effective solution, significantly reducing implementation costs compared to high-end drones like the Matrice 600.

## Visualization
A Tableau dashboard was developed to visualize drone paths, AQI measurements, and population density, aiding in the analysis of air quality across the campus.

## Conclusion
This project successfully demonstrated a cost-effective and efficient method for monitoring air pollution using drones. The genetic algorithm approach provided optimal path planning, ensuring comprehensive coverage and reliable AQI data collection.

## Future Work
Future work can explore incorporating drone charging times, expanding the model to include dynamic pollution patterns throughout the day, and refining the genetic algorithm for even greater efficiency.

## Authors
- Oojas Salunke
- Bilal Mufti
- Joey Ji
- Rishabh Goel
- Albert Ko

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
