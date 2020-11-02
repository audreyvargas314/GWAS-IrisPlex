# GWAS-IrisPlex
Calculating probabilistic scores of individuals having a certain eye color through Genome Wide Association Study

Abstract:
The project uses Genome Wide Association Study, a method that identifies genetic variants that are closely related to a specific trait (e.g. eye color). By obtaining genetic data from the 1,000 genomes project, we aim to develop a computer program that predicts the eye color of 2,504 individuals. We accomplished this by importing files containing genetic datasets, creating DataFrames, and implementing a multinomial regression model that calculates the probabilistic scores of each individual for having blue, brown, or other-colored eyes. A probability above 0.7 indicates a likely relationship between an individual and a specific eye color.

Data obtained from IrisPlex: A Sensitive DNA Tool for accurate prediction of blue and brown eye colour in the absence of ancestry information:
https://pubmed.ncbi.nlm.nih.gov/20457092/
