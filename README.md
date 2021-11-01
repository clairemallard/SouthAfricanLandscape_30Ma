# SouthAfricanLandscape_30Ma

=========

[![code](https://img.shields.io/badge/code-badlands-orange)](https://pypi.org/project/badlands)

## What’s in here?
You can use the following scripts and inputs to run landscape african models for the last 30 Ma coupled with four different dynamic topography estimations extracted from 4 different numerical models:
+ AY18 from Cao, W., Flament, N., Zahirovic, S., Williams, S., & Müller, R. D. The interplay of dynamic topography and eustasy on continental flooding in the late Paleozoic. Tectonophysics, 761, 108-121 (2019). 
+ M1 from Müller, R. D., Hassan, R., Gurnis, M., Flament, N., & Williams, S. E. Dynamic topography of passive continental margins and their hinterlands since the Cretaceous. Gondwana Research, 53, 225-251 (2018). 
+ M2 from Hassan, R., Williams, S. E., Gurnis, M., & Müller, D. East African topography and volcanism explained by a single, migrating plume. Geoscience Frontiers, 11(5), 1669-1680 (2020).
+ TX08 from Moucha, R., & Forte, A. M. Changes in African topography driven by mantle convection. Nature Geoscience, 4(10), 707-712 (2011). 

The input folder contains :
+ the initial topography corrected with water and sediment load "correctedwatertopo.csv" and the tectonic files generated Tecto****.csv or dz*.csv for the 4 tested dynamic topography models. 
+ common data used for all the models such as the erodability map "ero133.csv", the sea-level model "short_hybrid.csv", the climap maps or rainfall fixed values cli*.csv and the elastic thickness map "Tegpmlmeters.csv".

The script folder contains:
+ the *.xml scripts for all the models
+ the ipynb to run the models

## Documentation & Installation
https://badlands.readthedocs.io/
