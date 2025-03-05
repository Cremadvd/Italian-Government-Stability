# Gov_Stability
Developing a Bayesian network project to predict instability conditions in the Italian Government. 

The main objective of the project was the analysis of quantifiable data from all Italian governments from 1948 to 2022 through a Bayesian network in order to find evidence for political claims on the infamous instability of Italian executives and potentially discover unseen trends between all the considered elements.  

The project describes the entire pipeline of work, from dataset creation to model definition to prompting queries which test the model's effectiveness.

The project was developed in the context of the Fundamentals of Artificial Intelligence course in the Artificial Intelligence Master's Degree at the University of Bologna.

## Dataset

The dataset was built from scratch, starting from public data available from the official [Italian Senate website](https://www.senato.it/legislature/repubblica/governi-della-repubblica) and the related Wikipedia [article](https://it.wikipedia.org/wiki/Template:Governi_della_Repubblica_Italiana).
The dataset contains most of the quantifiable data available about each government, from the duration to the sizes of the majority and opposition during the initial confidence vote. A full description is available inside the provided Python notebook.

## Authors
- Davide Cremonini

## Technologies
![Python](https://img.shields.io/badge/Python-3.x-blue)
![NetworkX](https://img.shields.io/badge/NetworkX-3.x-green)
![pgmpy](https://github.com/pgmpy/pgmpy/actions/workflows/ci.yml/badge.svg?branch=dev)
