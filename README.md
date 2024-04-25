

**Genetic Algorithms on Cars**
Overview:
This project implements a genetic algorithm to optimize cars' navigation through a track with checkpoints. Each car is equipped with sensors that detect obstacles and determine movement directions based on predefined rules. The goal is to maximize the number of checkpoints crossed by evolving car behaviors across generations.

How it Works
Sensors: Cars are equipped with 5 sensors (left, top-left, top, top-right, right), detecting obstacles.
Chromosome: Each car has a chromosome dictating sensor combinations and corresponding movements.
Fitness: Cars earn scores based on checkpoints crossed. Higher scores indicate better performance.
Algorithm: Genetic algorithm iteratively evolves car behaviors, selecting, crossing over, and mutating chromosomes to optimize fitness.
Features
Selection: Choose fittest cars for reproduction.
Crossover: Combine genetic material of selected cars.
Mutation: Introduce variations in chromosome values.
Goal Finding: Identify cars completing all checkpoints.
Output Saving: Save chromosome outputs.
Display: Visualize algorithm output and test with provided code.
Instructions
Run main.py to start the genetic algorithm.
Modify algorithm parameters and track configuration in config.py if needed.
Check outputs in outputs directory.
Test with provided code in testing_section.py.
