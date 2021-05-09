M. Clifton PHY61008 project code
4 "Final Model ... Setup.ipynb" gives relevant model with initial parameters set up for specific scenario
"Average Pandemic Graphs ... .ipynb" gives averaged pandemic runs across 100 simulated runs (folder directory may require changing)
"Analysis ... .ipynb" gives graphs used in final report for different scenarios

SIRSto(incubation, dt, time, vac_start, vac_eff, A, randominfected)
incubation = disease incubation time in days
dt = timestep used in simulation
time = total time (days) simulation is run for
vac_start = vaccination start date (day)
vac_eff = vaccine efficacy (%)
A = value of R0
randominfected = defines whether model starts sim with given age infected profile (infected_healthy) or randomly distributes from N_inf
                 takes true or false value
