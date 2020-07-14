# ELE_Saavedra_etal_2020
This is the code in R associated with the manuscript:
"Structural forecasting of species persistence under changing environments" by
Serguei Saavedra, Lucas P. Medeiros, Mohammad AlAdwani. Ecology Letters.

The folder is comprised of 3 subfolders: code, data and results.

Inside code we provide the scripts to reproduce Figures 1-4.
Figures 1 and 2 need to run fig1_sim.R and fig2_sim.R, respectively, to generate the data from simulations. The code is commented, self explanatory, and has different options for LV models (these options are established in the folder functions in the script lotka_volterra.R). Then the corresponding plot can be generated by fig1_plots.R and fig2_plots.R.

Figures 3 and 4 need to run Fig3.R and Fig4.R to generate the results. This code does not generate figures only the quantitative information for predictions. All code is commented and self-explanatory.

Inside data we provide the matrices used in the study.

Inside results we save the results from running the simulations for Figures 1 and 2.
