# EDS 213 Group Project - Group 4

Cullen Molitor, Desik Somasundaram, Ryan Munnikhuis, and Julia Parish

## Our environmental question:
What is the effect of sea surface temperature on coral bleaching?

## Data
Coral bleaching, El Nino effect data, Sea surface temperature data

https://search.dataone.org/view/doi%3A10.5063%2FF1WQ024C

https://coralreefwatch.noaa.gov/satellite/bleachingoutlook_cfs/outlook_cfs.php

https://origin.cpc.ncep.noaa.gov/products/analysis_monitoring/ensostuff/detrend.nino34.ascii.txt

## Data Semantics
Our data analysis synthesizes two datasets to compute Simpson's diversity index. Our group researched how the vegan package computes the
Simpson's diversity index and searched for the subclass with species diversity that best aligned with our definition. 

This definition in the Cerrado concepts and plant community dynamics ontology best aligned with our definition:
"the simplest measure of the character of community that takes into account both the abundance patterns
and the species richness" (Begon et al., 2006).
ID: http://cerrado.linkeddata.es/ecology/ccon#SimpsonsIndex

