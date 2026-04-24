# Modelling the Hagelloch Measles Outbreak of 1861

In 1861 an outbreak of Measles occured in Hagelloch - a small, isolated German village.   

Dr. Albert Pfeilsticker visited the town each day, recording the spread of the disease and the complications arising from it. In 1992 Dr. Heike Oesterle augmented and re-analysed the dataset, making it available via the R surveillance package. 

I used this dataset on the Oxford Short Course [Infectious Disease Modelling: Applied Methods in R](https://lifelong-learning.ox.ac.uk/courses/infectious-disease-modelling-applied-methods-in-r) which teaches techniques for SEIR compartment modelling of infectious diseases.

Below an animation (built in R) showing the evolution of the disease both geographically and by compartment.

![Geographical Spread](outbreak_animation.gif)

The animation shows why Measles is such a difficult disease to manage. The long incubation period (~10 days) and high transmissability mean that there are likely to be many infections in the population before the first case appears.

Animation Code -> [HagellochVisualisation.Rmd](HagellochVisualisation.Rmd)    
Project Code -> [OutbreaksData.Rmd](OutbreaksData.Rmd)   
Project Report -> [Project Report](<Infectious Disease Modelling - Assignment 2 - Fox.pdf>)