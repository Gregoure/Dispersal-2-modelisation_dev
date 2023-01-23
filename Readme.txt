# MODELE PYTHON
# Stochastic simulation of virulence evolution in metapopulations

# THE PYTHON FILES

classes : Contains the classes of the model (OOP), The Sites, Events, and Evolving traits are defined in it.
Dev_Build_Network : Contains preliminary work for different spatial configurations implementations.
DirectMethod_v2 : Contains the initial gillespie algorithm for stochastic simulations
fonctions : Contains the functions called in the main model (To set a metapopulation, get propensities and intermediate computations 
for tau-leaping, and define the change in trait values for evolution).
Format_Dataframes : Old file for reducing the size of output
Params : File containing parameters inputs
program_with_evolution : Contains the main model loop and part for multisimulations
Dev_build_Network & Network function : Contain preliminary work for implementing dfferent spatial structures.

# The R FILES

Evaluation Tau-leap : Compares results between tau-leaping and direct method (Gillespie)
Rscript for ESS ~ Params : Main analysis of model outputs
Stochastic Extinction Measures : Not very useful but i keep it. Count occurences of stochastic extinction in simulations.

# The PDF FILES

rapport_eval : Results from the "Evaluation Tau-leap " script
Flux local : Forrester diagramm of the local model
Flux Metapop : Forrester diagram for the metapop model (transition between local equilibrias)

# The FOLDER 

Old : A lot of old things, should not be used.
Demography model : The files for the model run without evolution
