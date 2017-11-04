# GeoSim17-18
Repository for GeosimulationModelling (2017/2018)

Task: Adjust a model by adding a functionality to elaborate a research question.

Idea:

>>Hospitals can be set up at different locations within the system randomly.
>>The number of hospitals can be given as a input by the user (which will set a global variable).
>>A slider can be used to model how much area (or how many people or both) can a hospital cater to.
>>There can also be another slider to control what percentage of people get cured if they visit a hospital (e.g. 90%).



TO DOs:

Input # of hospitals - set it to a global variable in the code (hospitals set up randomly in the workspace)
Slider #1' for the max. capacity of the hospital - the maximum # of people who can get admitted in a hospital at any given time (assuming all hospitals have the same capacity) - intially using a static variable
Slider #2' for the area it can cater ("catchment area") - people from outside the catchment area cannot get into a hospital - initially using a static variable
Slider #3' for the probability of getting cured if someone visits a hospital - intially using a static variable

Notes: The time for getting cured can be modelled as a function of the time he was sick, say 0.5*sick-time (from the variable 'sick-time' already defined). If sick for 1 week then 0, 2 weeks then 1 and 3 weeks then 1 etc.

Copyright, License etc.

Netlogo Virus model by: Wilensky, U. (1998).  NetLogo Virus model.  http://ccl.northwestern.edu/netlogo/models/Virus.  Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.
License: Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License