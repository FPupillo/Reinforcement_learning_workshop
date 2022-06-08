# Reinforcement_learning_workshop
This is an introduction to reinforcement learning of choice data. The material of this repository
has been used for a workshop at the University of Granada on the 1st of June 2022. 
The workshop is divided into two parts: basic concepts and model fitting. 
The slides "reinforcement_learning_slides.pdf" constitutes a guide through the basic principles and applications of cognitive modeling in general and reinforcement learning models in particular. The .Rmd files `1.basic_concepts.Rmd` and `2.model_fitting.Rmd` contain practical examples of the principles illustrated in the slides. 
`Create.data.R` contains a script that creates the syntetic data that can be found in the `Data` folder.

## Main contents
- Introduction to cognitive modelling
- Introduction to reinforcement learning
- Pavlovian models
- Instrumental models
- Model simulation
- Parameter recovery
- Model recovery
- Model fitting and parameter estimation
- Model comparison
- Model Validation

## Structure of the repository
- `Data` - data used to fit the models 
- `helper_functions` - custom R functions used by the main scripts
- `likelihood_functions` - functions used to compute the likelihood of the choice data, given the models and the parameters
- `model_recovery` - custom scripts to do model recovery
- `output_files` - output of the scripts
- `simulation_functions` - functions used to simulate choice data given the models and the parameters