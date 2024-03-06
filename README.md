# ENAR 2024 Workshop 

Materials for the ENAR 2024 workshop "Bayesian Modelling of Epidemics: From Population to Individual-level Models"

Presented and created by Dr. Rob Deardon and Dr. Caitlin Ward

## Tentative Schedule

Morning (8:00 - 12:00pm)  
Part I: Introduction to Deterministic Epidemics Models and Bayesian Inference
Part II: Population-Averaged Models  

Afternoon (1:00pm - 5:00pm)  
Part IIIa: Individual-Level Models  
Part IIIb: Analyzing Infectious Disease Data with EpiILM  


## Installing Packages

All analyses will be done in R. 

The population-averaged models will be implemented using the R package NIMBLE. Before installing NIMBLE, you need a compiler and related tools such as make that R can use. Detailed instructions to do this are available at https://r-nimble.org/download.

Otherwise, packages used in the workshop can be installed using 

```
install.packages(c('nimble', 'ggplot2', 'outbreaks', 'plyr', 'splines', 
                   'geodata', 'sf', 'transformr', 'gganimate', 'EpiILM', 'igraph'))
```

