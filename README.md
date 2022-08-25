# Automating Chemical Kinetics Experiments

Chemical kinetics models describe how mixtures of compounds evolve over time and 
require many experiment with many types of data to create.
This repository contains software designed to automate creating such models
with a particular focus on shock-tube experiments.

Key features include:

- Using [Frhodo](https://github.com/Argonne-National-Laboratory/Frhodo) to automate analysis of shock tube experiments

## Installation

The repositories dependencies are defined using Anaconda and can be installed with

```bash

conda env create --file environment.yml --force
```
