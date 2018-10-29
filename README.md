# EmergencyWarnings
Course project for Introduction to Data Science 2018

# User instructions

This library provides functions for simulting the reach of emergency warnings in Finland. The functions require the csv files found in the repository. The library depends on numpy, pandas and matplotlib. In the folder Results there are plots of simulation results for different media and different areas.

How to use:
download all the files

import simulation1

Functions:

simulate_radio(set_area, pop_size, steps)

Simulate the reach of radio among a population. Based on average minutes listened per day.

simulate_tv(set_area, pop_size, steps):

Simulate the reach of television among a population. Based on average minutes watched per day.

simulate_sms(set_area, pop_size, steps):

Simulate the reach of sms warnings among a population. The function is based on cellphone ownership, and a 16 h per day active time of use.

Parameters

set_area: Choose an area for your simulation. Possible choises are 'Finland', 'Helsinki', 'Tampere', 'Kajaani' and 'Inari'.

pop_size: The population size, should be an integer. Due to rounding errors the actual population in the simulation might differ a bit from this parameter.

steps: Choose a number of simulation steps. For radio and television this means number of different broadcasts of the warning. The interpretation is different with sms, the different steps represent time intervals for checking cellphone.
