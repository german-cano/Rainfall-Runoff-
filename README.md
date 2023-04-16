# Rainfall-Runoff
Final project for the course Laboratory of Computational Physics, University of Padova.

Rainfall-runoff modelling remains still an unresolved problems among hydrological sciences. Along history several aproaches have been tried such as predict the discharge as a function of precipitation events or refined models with explicit properties of the catchments. The computational cost of these models is progresively increasing so usually less complex models are used even though they are not that reliable.

Here we tried to use the advantages of deep neural networks in terms of computational costs and prediction capacity to tackle this problem. Specifically,the principal purpose of this project is to integrate the train of a LSTM neural network with the summary statistics provided by an econder. We want to verify if the latter, enclosing the main characteristics of different hydrological basins, could help to improve prediction for those catchments with poor informations.
