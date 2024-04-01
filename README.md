# quantmacroproject

This repository contains data for replicate Deleidi and Mazzucato (2021)
DatasetD2018.csv cointains quarterly data from 1947:Q1 to 2018:Q3. All data are nominal, obtained from the BEA-NIPA (the same BEA code of Deleidi and MAazzucato).

## Gordon's transformation

datadt.csv are divided by the lagged values of the real trend GDP computed through an Hodrik-Prescott filter (using statsmodel with lambda = 10000). They include also data on non-defense spending in R&D
