# Alternatives to Contour Visualizations for Power Systems Data

The scripts in this repo are for handling DSS distribution grid data, primarily from the SFO Smart Grid. The various directories in src/ are from:
1. p13u: This is the code to go with the paper "Alternatives to Contour Visualizations for Power Systems Data" by Isaiah Lyons-Galante, Morteza Karimzadeh, Samantha Molnar, Graham Johnson, and Kenny Gruchalla. It uses a feeder within p13u with about 24,000 buses.
2. smbl_envc_6: this is another section of the SFO grid, but this one includes more types of grid components such as transformers, batteries, and solar panels. It also has time series of bus voltages.
3. evsatscale: this contains some of the code for processing the EV charging simulations. 
4. 10x: This code is for scaling up the analysis in p13u to a 10x larger grid with about 300,0000 buses. 
