# Project Title: LTM Enhancement for COVID-19 Modeling

## Overview
This project aims to develop and enhance a Linear Threshold Model (LTM) for simulating the dynamics of COVID-19 transmission within a population. The LTM is designed to emulate individual-level variability in susceptibility and integrate it with epidemiological models like the SIR model for more accurate predictions.

## Authors
- Dylan Small
- Tejas Pradeep
- Anjana Chamarthi

### Affiliation
Georgia Institute of Technology, United States

## Contact
- Dylan Small: dylansmall@gatech.edu
- Tejas Pradeep: rptejas@gatech.edu
- Anjana Chamarthi: achamarthi6@gatech.edu

## Abstract
The COVID-19 pandemic highlighted the need for models that account for individual variability in disease susceptibility. Our project develops a Linear Threshold Model (LTM) representing individuals as nodes in a network with varying thresholds of influence for infection. The model is integrated with other models such as the SIR model to refine predictive capabilities.

## Problem Definition
The project focuses on developing an LTM to account for individual-level susceptibility in modeling COVID-19 spread. The challenge lies in capturing the complexity of human mobility and interactions and integrating the LTM with more complex epidemiological models for better predictions.

## Previous Work and Literature Review
A comprehensive review of relevant literature on LTMs, social network influence models, and various disease spread models is conducted. This includes an examination of the Independent Cascade Model, Community Influence Evaluation, and different variations of the SIR model.

## Data Collection
The dataset comprises weekly snapshots of COVID-19 epidemiology in the United States, including confirmed cases, deaths, recoveries, and tests. The data is sourced from the CDC.

## Mathematical Background
Understanding of graph theory, optimization theory, and differential equations is crucial for modeling. Python libraries like numpy, matplotlib, seaborn, and scipy.integrate are used for simulations.

## Model Definition and Algorithms
The project employs a combination of the LTM with SIR and other models, using a network-based approach to simulate disease spread. The models are implemented using Python, with a focus on integrating LTM thresholds and activations in disease transmission rates.

## Model Evaluation
A combination of weighted mean-squared-error loss, normalized error metrics, visual analysis, and comparative analysis is used to evaluate model performance.

## Experiments and Results
Various differential-equation-based models are tested with and without LTM augmentation. The dataset is split into training and validation sets, with grid search and optimization techniques used for calibration. The SIRS model, combined with the LTM, shows the most promising results.

## Challenges and Future Work
The project addresses challenges in data accessibility, LTM implementation complexity, and simulation validation. Future work can focus on enhancing the dataset, refining the SIRS model, and incorporating additional factors like vaccination data.
