# Agent-Based Model on the Stigmergic Emergence of Task Partitioning in Leaf-Cutting Ants

![ABM video](./title_video.gif)

**Authors of Model:** Me, Patrick Govoni & Kin Ho Chan <br>
**Supervisors:** Piet Van Den Berg & Prof. Tom Wenseleers <br>
**Affiliation:** Department of Biology, KU Leuven <br>
**Group:** Lab of Socioecology & Social Evolution <br>
**Timespan:** 2020-Present (Currently Revising Unpublished Manuscript)

**Abstract:** Social insects owe their widespread success to their ability to efficiently coordinate behavior to carry out complex tasks. Several species of leaf-cutting ants employ an advanced type of labor division referred to as task partitioning, where the foraging task of retrieving leaves as a substrate for their fungal gardens is divided between those that cut and drop leaves from the top of a tree and others that retrieve the leaves back to the nest. How such complex self-organized behavior could evolve is not entirely clear. Here we use an agent-based model to show that task partitioning can in principle evolve based on a minimal set of traits describing indirect communication between individuals through the environment, also known as stigmergy. We demonstrate that partitioned leaf retrieval is favored as tree height increases, where bypassing costly trips up and down the tree becomes significant to colony fitness. The concepts explored could in principle be applied to engineered collective systems to dynamically modulate labor division.

**Jupyter Notebook Files:** <br>
The following notebooks describe an agent-based model (ABM) used to demonstrate the emergence of task partitioning in the foraging behavior of leaf-cutting ants with regards to two behavioral traits and leaf dropping length. The files build the system by:

- [setting up the model using an object-oriented Mesa framework, detailing how to run/display the simulation and how to iterate model runs for data collection/visualization](https://nbviewer.org/github/pgovoni21/ants-task-partitioning-ABM/blob/main/ABM.ipynb)
- [using the iterated data to plot heatmap landscapes, showing the relationship between ant output as well as behavior in relation to different trait combinations](https://nbviewer.org/github/pgovoni21/ants-task-partitioning-ABM/blob/main/landscapes.ipynb)
- [simulating evolution from generalist to task-partitioned collective behavioral strategies via fitness proportionate (roulette wheel) selection and Gaussian mutation](https://nbviewer.org/github/pgovoni21/ants-task-partitioning-ABM/blob/main/evolution.ipynb)
- [approximating ant behavior from a deterministic approach, using differential equations to describe ant movement and decision-making](https://nbviewer.org/github/pgovoni21/ants-task-partitioning-ABM/blob/main/deterministic-approx.ipynb)

## License

Copyright © 2022 [Patrick Govoni](https://github.com/pgovoni21). <br />
This project is [MIT](https://github.com/pgovoni21/ABKinase-bistability-traveling-front-dynamics/blob/main/LICENSE) licensed.
