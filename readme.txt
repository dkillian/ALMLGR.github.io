Note: The code must be run in Stata version 15 or 16. Earlier versions will encounter errors.

To replicate all results from start to finish:

[0 OPTIONAL] Run build/Clean_data_export_stata.R in R
[1]          Run analysis/Analysis.do in Stata
[2]          Run analysis/Paper_figures in R

The folder structure is organized as follows:

--> code
-----> build
---------- Clean_data_export_stata.R
		   (Builds the all_city.dta Stata file from input CSVs.)
-----> analysis
---------- Analysis.do
		   (Replicates the main results.)
---------- Paper_figures.R
		   (Formats the figures as in replication paper)
--> data
-----> input
		   (Raw input files digitized from historical sources.)
-----> output
---------- all_city.dta 
		   (Contains all necessary information to replicate the main regressions.)
--> results
