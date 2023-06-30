# HDSC_STAGE-C_Quiz
Tag-Along Jupyter Notebook file for Stage C Quiz for Hamoye Data Science Internship 2023.


## Machine Learning: Classification - Managing the Quality Metric of Global Ecological Footprint

The dataset used in this course was obtained from the National Footprint and Biocapacity Accounts. 
It provides Ecological Footprint per capita data for years 1961-2016 in global hectares (gha).
The National Footprint and Biocapacity Accounts (NFAs) measure the ecological resource use and resource capacity of nations from 1961 to 2016.
The calculations in the National Footprint and Biocapacity Accounts are primarily based on United Nations data sets.

This data includes total and per capita national biocapacity, the ecological footprint of consumption, the ecological footprint of production and total area in hectares.

Data Source: https://data.world/footprint/nfa-2019-edition

## Dataset Description

### Stability of the Grid System

Electrical grids require a balance between electricity supply and demand in order to be stable. 
Conventional systems achieve this balance through demand-driven electricity production. 
For future grids with a high share of inflexible (i.e., renewable) energy sources, the concept of demand response is a promising solution. 
This implies changes in electricity consumption in relation to electricity price changes. 
In this work, we’ll build a binary classification model to predict if a grid is stable or unstable using the UCI Electrical Grid Stability Simulated dataset.

### Dataset Attributes Information

It has 12 primary predictive features and two dependent variables.

#### Predictive features:

1) 'tau1' to 'tau4': the reaction time of each network participant, a real value within the range 0.5 to 10 ('tau1' corresponds to the supplier node, 'tau2' to 'tau4' to the consumer nodes);
2) 'p1' to 'p4': nominal power produced (positive) or consumed (negative) by each network participant, a real value within the range -2.0 to -0.5 for consumers ('p2' to 'p4'). As the total power consumed equals the total power generated, p1 (supplier node) = - (p2 + p3 + p4);
3) 'g1' to 'g4': price elasticity coefficient for each network participant, a real value within the range 0.05 to 1.00 ('g1' corresponds to the supplier node, 'g2' to 'g4' to the consumer nodes; 'g' stands for 'gamma');

#### Dependent variables:

1) 'stab': the maximum real part of the characteristic differential equation root (if positive, the system is linearly unstable; if negative, linearly stable);
2) 'stabf': a categorical (binary) label ('stable' or 'unstable').
