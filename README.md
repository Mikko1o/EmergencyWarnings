# EmergencyWarnings
Course project for Introduction to Data Science 2018

# User instructions

This library provides functions for simulting the reach of emergency warnings in Finland. The functions require the csv files found in the repository. The library depends on numpy, pandas and matplotlib. In the folder Results there are plots of simulation results for different media and different areas.

How to use:
1. Download all the files
2. Import project in jupyter and open simulation1.
3. Modify simulation functions with your parameters as explained below.
 
# Functions
simulate_radio(set_area, pop_size, steps) #Simulates the reach of radio among a population based on average minutes listened  per day.

simulate_tv(set_area, pop_size, steps) #Simulates the reach of television among a population based on average minutes watched per day.

simulate_sms(set_area, pop_size, steps) #Simulates the reach of sms warnings among a population based on cellphone ownership, and a 16 h per day active time of use.

# Parameters

set_area: Choose an area for your simulation. Possible choises are 'Finland', 'Helsinki', 'Tampere', 'Kajaani' and 'Inari'.

pop_size: The population size, should be an integer. Due to rounding errors the actual population in the simulation might differ a bit from this parameter.

steps: Choose a number of simulation steps. For radio and television this means number of different broadcasts of the warning. The interpretation is different with sms, the different steps represent time intervals for checking cellphone.
