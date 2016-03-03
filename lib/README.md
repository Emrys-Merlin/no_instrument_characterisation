# Evaluation scripts directory
This directory contains the scripts to evaluate the data provided by
the DOASIS evaluation routine.


## Workflow
* The DOASIS data (in the standard configuration called
  YYYY_MM_DD_fitResults_ppb.dat) should be copied into a data folder and
  renamed to #{name}_raw.csv.

* Next the script "Doas Conversion" should be applied to extract the
  necessary columns and rename them (the DOASIS nomenclature is just
  aweful).

* Afterwards you use the appropriate script for your task

** Ozone Evaluation: If you want to check how much Ozone your
   generator prduces and how much NO_2 it generates on the way, this is
   your script.

** NO Computation: If you measured NO_x data and NO_2 data you can
   retrieve the NO data with this script and merge the data sets.

