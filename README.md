# EDS 213 Group Project - Group 4

Cullen Molitor, Desik Somasundaram, Ryan Munnikhuis, and Julia Parish

## Our environmental question:
What is the effect of sea surface temperature on coral bleaching?

## Data
Search terms: Coral bleaching, El Nino effect data, Sea surface temperature data

Data Sources:
James P Gilmour, Kylie L Cook, and Nicole M Ryan. 2021. Scott Reef and Rowley Shoals Coral Bleaching Data. Environmental Data Initiative. https://pasta.lternet.edu/package/metadata/eml/edi/952/1.

NOAA/ National Weather Service National Centers for Environmental Prediction Climate Prediction Center Oceanic Niño Index (ONI) https://origin.cpc.ncep.noaa.gov/products/analysis_monitoring/ensostuff/detrend.nino34.ascii.txt


## Data Log 

The data log tracks the metadata of datasets collected for our analysis. Metadata within the data log includes: the URL or identifier to the data source, a brief description of the dataset, date the data was last accessed, authors and organizations of data, contact information of authors, download path to data set, data set name in sharefile, email of team member who downloaded the data, and whether the data was used in the analysis. 

## Data Management Plan

### Project Team Roles
Desik Somasundaram will be in charge of downloading the data. Cullen Molitor is responsible for developing and maintaining the scripts for data processing and analysis. Due to the dataset size being relatively small, the time needed to manage the data is not expected to be more that 2-4 hours. Ryan Munnikhuis will be responsible for managing the data log. The data will be preserved by Julia Parish.

### Data Management and Analysis Workflow
Coral data will be downloaded for the local coral reef ecosystems (currently limited to Rowley Shoals (RS) and Scott (SR) reef systems in Northwest Australia). Data on the monthly input to Ocean Nino Index will be used to compute the 3 month mean of the temperature anomaly. Both datasets will be combined to align the time periods. Then a Simpson’s diversity index will be computed using the functions available in the vegan R package to draw the potential relationships between the temperature anomaly and coral species diversity. The data will be preserved until the Simpson’s diversity index methodology has been superseded by more significant research. Our group will be using a KNB project repository to preserve our data due to their reputation, reliability and commitment to the future in case of company changes. 

### Potential Legal Implications
Currently, there are no legal constraints associated with acquiring, using and sharing the project data that we are aware of.

## Data Semantics
Our data analysis synthesizes two datasets to compute Simpson's diversity index. Our group researched how the vegan package computes the
Simpson's diversity index and searched for the subclass with species diversity that best aligned with our definition. 

This definition in the Cerrado concepts and plant community dynamics ontology best aligned with our definition:
"the simplest measure of the character of community that takes into account both the abundance patterns
and the species richness" (Begon et al., 2006).
ID: http://cerrado.linkeddata.es/ecology/ccon#SimpsonsIndex

