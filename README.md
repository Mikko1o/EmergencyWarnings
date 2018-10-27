# EmergencyWarnings
Course project for Introduction to Data Science 2018

# User instructions

This library provides functions for simulting the reach of emergency warnings in Finland. The functions require the csv files found in the repository. The library depends on numpy, pandas and matplotlib.

How to use:
download all the files
import simulation1

Functions:
simulate_radio(set_area, pop_size, steps)

simulate_tv(set_area, pop_size, steps):

simulate_sms(set_area, pop_size, steps):

Parameters
set_area: Choose an area for your simulation. Possible choises are 'Finland', 'Helsinki', 'Tampere', 'Kajaani' and 'Inari'.
pop_size: The population size, should be an integer. Due to rounding errors the actual population in the simulation might differ a bit from this parameter.
steps: Choose a number of simulation steps. For radio and television this means number of different broadcasts of the warning. The interpretation is a different with sms, the different steps represent time intervals for checking cellphone.
