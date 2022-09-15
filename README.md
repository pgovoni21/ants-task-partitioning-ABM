# Agent-Based Model on the Stigmergic Emergence of Task Partitioning in Leaf-Cutting Ants

![ABM video](./title_video.gif)

**Authors of Model:** Me, Patrick Govoni & Kin Ho Chan <br>
**Supervisors:** Piet Van Den Berg & Prof. Tom Wenseleers <br>
**Affiliation:** Department of Biology, KU Leuven <br>
**Group:** Lab of Socioecology & Social Evolution <br>
**Timespan:** 2020-Present (Submitted Manuscript)

**Abstract:** Social insects owe their widespread success to their ability to efficiently coordinate behaviour to carry out complex tasks. Several leaf-cutter ant species employ an advanced type of division of labour known as task partitioning, where the task of retrieving leaves is distributed between workers specializing in cutting and dropping and those that collect the fallen leaves. It is not entirely clear how such highly coordinated behaviour can evolve, as it would seem to require the simultaneous mutations of multiple traits. Here, we use an agent-based simulation model to show how task partitioning in leaf-cutter ants can gradually evolve by exploiting stigmergy (indirect coordination through the environment) through gravity (leaves falling from the treetop on the ground forming a cache). Our simple model allows independent variation in two core behavioural dimensions: the tendency to drop leaves and the tendency to pick up dropped leaves. Task partitioning readily evolves even under these minimal assumptions through adaptation to an arboreal environment where traveling up and down the tree is costly. Additionally, we analyse ant movement dynamics to demonstrate how the ants achieve efficient task allocation through task switching and negative feedback control.

**Jupyter Notebook Files:** <br>
The following notebooks describe an agent-based model (ABM) used to demonstrate the emergence of task partitioning in the foraging behavior of leaf-cutting ants with regards to two behavioral traits and leaf dropping length. The files build the system by:

- [setting up the model using an object-oriented Mesa framework, detailing how to run/display the simulation and how to iterate model runs for data collection/visualization](https://nbviewer.org/github/pgovoni21/ants-task-partitioning-ABM/blob/main/ABM.ipynb)
- [using the iterated data to plot heatmap landscapes, showing the relationship between ant output as well as behavior in relation to different trait combinations](https://nbviewer.org/github/pgovoni21/ants-task-partitioning-ABM/blob/main/landscapes.ipynb)
- [simulating evolution from generalist to task-partitioned collective behavioral strategies via fitness proportionate (roulette wheel) selection and Gaussian mutation](https://nbviewer.org/github/pgovoni21/ants-task-partitioning-ABM/blob/main/evolution.ipynb)
- [approximating ant behavior from a deterministic approach, using differential equations to describe ant movement and decision-making](https://nbviewer.org/github/pgovoni21/ants-task-partitioning-ABM/blob/main/deterministic-approx.ipynb)

## License

Copyright © 2022 [Patrick Govoni](https://github.com/pgovoni21). <br />
This project is [MIT](https://github.com/pgovoni21/ABKinase-bistability-traveling-front-dynamics/blob/main/LICENSE) licensed.
