# COFIT (Scientific Reports)
COVID-19 modified PSEIRD(S) model

This repository includes the fitteia(R)[http://fitteia.org] PSEIRD(S) model fit templates to analyse COVID-19 data series
for the paper accepted in Scientif Reports "A differential equations model-fitting analysis of COVID-19 epidemiological data to explain multi-wave dynamics"

You can try first to learn how to use fitteia by fitting the basic SIR-based compartment model to the statistical data of the people infected with coronavirus. 
https://sites.google.com/tecnico.ulisboa.pt/fitteia/home/covid-19?authuser=0

When you are able to use fitteia with some proficiency you can download one of the templates available in this repository that were used to fit the data in the paper pubished in Scientifc Reports - "A differential equations model-fitting analysis of COVID-19 epidemiological data to explain multi-wave dynamics"

Register/Login at http://fitteia.org into your fitteia account and select your working folder by clicking on the respective link in the page.

click fitter->Upload, browse the ".sav" files you have downloaded from this repository and select one to upload. The file that includes "AdditionalCode" in the name can only be fully used by users with added privileges for writing their own C code. If you wish to try this more compact version of the template, please contact one of the authors.

Choose->Upload->Return to the working folder.

Select fitter->Master mode by clicking on the respective link.

Select the file Master_ScientificReports_PT_Template and click Recover.

Start by fitter->Plot to plot the last fits recorded.

In "Data" text box find the DATA blocks that start with "# DATA SEIRD=...". Some of these sets are virtual data block sets for plotting purposes only (compartments for which there is no data available). A TAG is assigned to each data block so that they can be selected or unselected using the list below the model parameters. Keep in mind that, if you select a virtual data set, then you cannot perform a fit (unless all parameters are fixed, which, in practise, is equivalent to plotting). 

Play with the fits and be aware that you are fitting the solutions of a set of ordinary differential equations to a set of actual data. Do not try to free all parameters at once and be mindful of the magnitude differences between each compartment. Aditional help can be found at http://fitteia.org.

In this repository you will find also a template for the fitteia->Plotter module that contains a comparison between the projections made using the model fitted parameters to the data untill 14 March 2021.

Please contact one of the authors in case of need some assistence.

Pedro Sebastião
Maria Beira
