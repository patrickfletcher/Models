# Model of corticotroph electrical activity

These files were used to generate figures in the manuscript: 

"Modeling the diversity of spontaneous and agonist-induced electrical activity in anterior pituitary corticotrophs" by Patrick Allen Fletcher, Hana Zemkova, Stanko S. Stojilkovic, and Arthur Sherman. Journal of Neurophysiology, 2017, Vol. 117 no. 6, DOI: [10.1152/jn.00948.2016](http://dx.doi.org/10.1152/jn.00948.2016)

# Usage

Use [XPPaut](http://www.math.pitt.edu/~bard/xpp/xpp.html) to run the simulations. 

- JNP17.ode was used to generate trajectories in Figures 3, 4, 6, and 7
- JNP17er.ode was used to generate trajectories in Figure 8


# Notes:

- Default parameter values are set to produce low-frequency spiking
- When changing parameters to match different figure panels, make sure to run the simulation to steady state before running a pulse simulation. To disable the pulse, either set tpulse>total or keep the pulse parameter of interest (eg. gCRHpulse) set to zero.