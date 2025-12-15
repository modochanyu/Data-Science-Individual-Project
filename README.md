This code analyses a dataset compiled by Miller (2012) on geographical ranges, fungal pathogen species richness, and other functional traits of plant species native to the USA.

Link to paper: https://www.journals.uchicago.edu/doi/10.1086/663676
Link to dataset: https://datadryad.org/dataset/doi:10.5061/dryad.q1p71q5q

This dataset has since been cleaned up for use here: see pathogen_richness.csv attached on GitHub

## explanations of columns in the dataset: ##

CI: citation index: a measure of how often the species in question has been studied. Was calculated by number of papers mentioning it on Web of Science minus 1, all log transformed.
Loght: log transformed maximum height value recorded for the species
ANG_GYM: whether the species is an angiosperm (flowering plant) or gymnosperm (cone-bearing plant)
native: binary variable indicating whether the species is native to North America (1) or not (0)
Functional_group: classification of the sort of plant the species is: G-Tree or A-tree: trees that are angiosperms or gymnosperms; shrubs: woody species less than 7m in height; herbs: any other species
logGeoRangeST: estimate of the geographical range of the species by adding together the areas of all US states where it is found and log transforming this value
LogGeoRangeCO: estimate of the geographical range of the species by adding together the areas of all counties within US states where it is found and log transforming this value
LogPSR: log transformed number of fungal pathogen species recorded on the species


Before starting, add the packages pandas, seaborn, and scikit-learn
