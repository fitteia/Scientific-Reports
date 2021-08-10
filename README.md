# COFIT (Scientific Reports)
COVID-19 model PSEIRD(S) 

This repository includes the fitteia(R)[http://fitteia.org] PSEIRD(S) model fit templates to analyse COVID-19 data series and also the supplementary material 
for the paper accepted in Scientif Reports "A differential equations model-fitting analysis of COVID-19 epidemiological data to explain multi-wave dynamics"

You can try first to use fitteia to fit the basic SIR-based compartment model to the statistical data of the people infected with coronavirus. 
In particular, you can try to fit PSEIRD(S) model to the data collected for IT, DE, CA, IR, CH, JP, IL, AT, KR, IS, and NZ [https://github.com/CSSEGISandData/COVID-19].

Choose and download to your computer the latest contents of fitteia/COFIT repository and unzip the file.

Register/Login at http://fitteia.org into your fitteia account and select your working folder by clicking on the respective link in the page.

click fitter->Upload, browse the ".sav" files you have downloaded and select one.

Choose->Upload->Return to the working folder.

Select fitter->Expert mode by clicking on the respective link.

Select one of the files starting with IT, DE, CA, IR, CH, JP, IL, AT, KR, IS, NZ and click Recover.

Start by fitter->Plot to plot the last fits recorded.

In "Data" text box find the DATA blocks that start with "# DATA SEIRD=1", with 2, 3, 4, 5, 7, 8, 9, and 14, and set the flag "EXCUDE yes" for each one. These are virtual data block sets for plotting purposes only (compartments for which there is no data available). You can now play either with "Fit" or "Plot"

Play with the fits and be aware that you are fitting the solutions of a set of ordinary differential equations to a set of actual data. Aditional help can be found at http://fitteia.org.

When you are able to use fitteia with some proficiency you can upload one of the templates below used to fit the data in paper pubished in Scientifc Reports 
"A differential equations model-fitting analysis of COVID-19 epidemiological data to explain multi-wave dynamics"
