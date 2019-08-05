# INLA-GEOMED2019
Spatial and Spatio-Temporal Bayesian Models with R-INLA

Workshop goal

Provide an introduction to the Integrated Nested Laplace Approximation approach
(INLA) for the analysis of spatial and spatio-temporal data at the small area level.

First part 

We will start with setting the basis of small area studies and then introduce INLA for Bayesian inference. We will focus on hierarchical structures and spatially structured random effects through conditional autoregressive specifications; we will then extend the approach to include temporal dependency and touch briefly on spatio-temporal
interactions. 

Second part

After the coffee break we will go through a tutorial to see the specific command lines and options to run INLA on the type of data/models presented in the first part. This shiould take around 30-45 minutes. After this participants will have the opportunity of running a practical on spatial and spatio-temporal disease mapping on their computers. It is recommended that people attending are familiar with R (https://www.rproject.org/) and with the basic of the Bayesian approach (this will only be very briefly recap before presenting the INLA approach). 

It would be beneficial if attendees could bring their laptop with the latest version of R installed. The list of R packages to be installed before the workshop is below:

INLA (using install.packages("INLA", repos=c(getOption("repos"), INLA="https://inla.r-inla-download.org/R/stable"), dep=TRUE))

rgdal, sp, spdep (for the maps, using install.packages(c("rgdal","sp","spdep"))
