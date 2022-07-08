# Taskography

This is the landing page for *Taskography: Evaluating robot task planning over large 3D scene graphs*, presented at CoRL2021.
For a brief overview of the work, please refer to our [project webpage](https://taskography.github.io/).


### :building_construction:	Taskography-API
**[To API.](https://github.com/taskography/taskography-api)** 
A simple API for sampling symbolic planning tasks in large-scale 3D scene graphs. 
Provides support for the following: (1) hierarchical-symbolic graph construction; (2) task sampling; (3) trajectory sampling; (4) procedurally generated environment wrappers.

### :earth_americas: PDDLGym Environments
**[To Envs.](https://github.com/taskography/pddlgym)**
Official benchmark environments in Planning Domain Definition Language ([PDDL]((https://planning.wiki/ref/pddl/domain))) instantiable in [gym](https://github.com/openai/gym) environment interfaces.

### :rocket: Modern Planners (coming soon)
**[To Planners.](https://github.com/taskography)**
A collection of learning-based planners, SCRUB, and SEEK planners found to be most performant for 3D scene graph planning.

### :airplane: Classical Planners
**[To Baselines.](https://github.com/agiachris/pddlgym_planners)**
A package interfacing all satisficing and optimal symbolic planners benchmarked in Taskography with Python.

### :house: Development Repository
**[To Dev.](https://github.com/taskography/pddlgym)**
An in-house repository that contains the [official benchmark results](https://github.com/taskography/3dscenegraph-dev/tree/main/scenegraph/exp-official) in `.json` file format, along with original scripts used to generate all Taskography planning domains.
The majority of this code has been repurposed in Taskography-API.

---
## Citation
If you find any of packages useful, please consider citing our work:

```
@inproceedings{agia2022taskography,
  title={Taskography: Evaluating robot task planning over large 3D scene graphs},
  author={Agia, Christopher and Jatavallabhula, {Krishna Murthy} and Khodeir, Mohamed and Miksik, Ondrej and Vineet, Vibhav and Mukadam, Mustafa and Paull, Liam and Shkurti, Florian},
  booktitle={Conference on Robot Learning},
  pages={46--58},
  year={2022},
  organization={PMLR}
}
```
