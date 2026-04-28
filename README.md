Empirical-study-on-one-dimensional-Cutting-Stock-Problem

This repository contains the implementation of the models and procedures used in the empirical study for the one-dimensional Cutting Stock Problem (CSP). The material is intended to accompany the paper and provide transparency and reproducibility of the computational experiments.

Repository Structure

The repository is organized into six main .txt files, each corresponding to a specific component of the proposed approach:

1. Arcflow_Model.txt

Integer Programming model based on arc-flow formulation for solving the Cutting Stock Problem.
This model represents feasible cutting patterns implicitly through a network flow structure.

2. Arcs_Generation.txt

Procedure responsible for generating the set of arcs used in the arc-flow model.
These arcs define the state transitions in the underlying network representation.

3. Arcs_to_Patterns.txt

Post-processing function that converts the arc-based solution into explicit cutting patterns along with their respective frequencies.

4. CSP_Model.txt

Integer Programming model for solving the CSP using a pattern-based formulation.
This model is used within a heuristic framework that relies on a pre-generated set of cutting patterns.

5. Cutting_Patterns_Generation.txt

Procedure for generating feasible cutting patterns prior to solving the pattern-based model.
This step is essential for the heuristic filtering approach.

The code is provided as supplementary material for the paper:

Empirical Study on One-Dimensional Cutting Stock Problem

It is intended to:

Support reproducibility of the computational results
Provide implementation details of the proposed models
Serve as a reference for future research
Notes
All files are provided in .txt format for portability and ease of inspection.
The implementations focus on clarity and alignment with the formulations described in the paper.
Minor adaptations may be required depending on the solver or programming environment used.
