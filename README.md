# MAPDB
Final project of the course Management and Analysis of Physics Datasets mod. B - Physics of Data, UNIPD

The project aimed to develop a pipeline for reconstructing the trajectories of cosmic rays passing through drift chambers at the INFN center in Legnaro (PD), while fully leveraging parallel processing. This was achieved using a cluster of three virtual machines and the Spark framework, which allowed the pipeline to scale efficiently with minimal changes to the code, which was written in python. The reconstruction relied on a first-approximation least squares fit, with additional techniques explored to handle outliers by exploiting the chamber geometry. The Benchmarking.ipynb file used to evaluate processing times across a wide range of cluster configurations.
