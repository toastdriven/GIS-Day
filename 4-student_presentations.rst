=====================
Student Presentations
=====================

Environmental & Morophological - Jessica Rodriguez
==================================================

* Measure of species in a geographic area
* Known for statistical analysis
* Used Icterus (New World bird) due to plentiful information
* N. Alaska to Chile

* Import from NatureServe into Arc
* Presence/Absence matrix per degree for density
* Then added altitude/precip into the model

* Statistical measure
  * Altitude - no significance
  * Precip - no sig
  * Latitude - most sig

* New hypothesis - Is there a correlation between the morpho & phylogenetic
  differences of the bird genus with the environment they live?


Mapping Biomass Distribution Potential - Michael Schaetzel
==========================================================

* Map of biomass facilities in US - biomasspower.com
  * High density in the midwest
  * NARL tonnage per county map
  * High ethanol concentrations
* Counties capable of turning biomass into electricity
  * Crop residue
  * Yard waste
  * Iowa & Illinois have high density, lighter in Kansas
* Biomass Energy Potential
  * Could supply up to 14% of nation's power (instead of the actual 1%)
  * Carbon neutral-combustion of biomass is natural
  * Improved crop residue management has potential to benefit:
    * environment
    * producers
    * economy
* In the chem dept, ground up a variety of wastes to measure potential energy.
  * Dirty diaper wins with 11k BTU/lb
* Densification (brick)
  * Need more efficient burning
* GIS role in Carbon Neutrality
  * Site planning
  * Best uses of land management
  * Commercial distribution of bricks


Comparing Remotely-Sensed Data Products Via Ecological Niche Modeling - Sarah ____
==================================================================================

* ENM (Ecological Niche Modeling)
* Problem
  * No quantitative performance evalutations done on satelite imagery
  * Which input data types are most robust
  * Does index manipulation affect output
  * Extrapolation between regions
* 3 MODIS vegetation indicies (EVI, LSWI, NDVI)
  * Bird Flu in the Middle East
* Index category (EVI, LSWI, NDVI)
* Index Type (monthly layers)
* Model level (regions)
* 144 runs producing distribution maps
  * Modified ROC
  * Provides area under the curve
  * p - Bootstrap values (small values good)
* Results mapped
  * Regions at high risk over the monthly vs. overall
* Index Cat - no sig
* Index Type - no sig
* Model Level - Significant
* Extrapolation = bad & should be avoided
* Predictions more robust when trained/tested in the same region


Spatial Analysis of Meth Lab Seizures for Jefferson County - Aasron Gilbreath
=============================================================================

* History of Meth Labs
  * Started in West in 1960s, Midwest by 2000s
* Data is hard to get.
  * By country if you're lucky.
* JoCo & St. Louis had good data
* Missouri #1 producer
* Successful geocode of ~2k addresses
* NN analysis in Arc
* Aggregate up to census block group
* Regression analysis
* Spatial autocorrelation - was significant
* Least squares regression
* Many variables (demographics / environmental)
* Unemployment & distance from police dept highly correlation
* Lag Model
  * Much better than the least squares
  * Meth labs diffuse into surrounding area


Effects of Irrigation on Great Plains & Midwest Precip Processes - David Huber
==============================================================================

* Overview
  * Historical & Conceptual Review
  * Description of modeling approach
  * Results
  * Conclusion
* Historical Changes int Precip
  * Map of irrigation
  * Heavy in Iowa, Illinois, Missouri, Indiana
* review of irrigation's effects
  * Increases water vapor in air
  * Cools surface & lower atmosphere
* Model setup
  * Weather Research
  * Modified USGS 24 Cat Land Cover Scheme
  * Two experiments (Control & Irrigated)
    * Every day over 2 months in 2001
  * Differences Analyzed
    * precip, radiation
* Model domain
  * Region type
* Radiation Differences
  * Change in Sensible flux
  * "  " in Latent Flux
  * "  " in Upwelling Longwave
  * "  " in Downwelling Longwave
  * Slight Decrease over irrigationed region
  * Increase in net radiation
  * Cross the board decrease, most significant
* Flow Regimes
  * Affect of water & air flow
  * Slight decrease in wind to the east, slight increase to the west
* Precip Differences
  * Large increase
* Irrigation alters the radiation balance & water budget
* Alters flow of low level jetstream


GIS & object oriented ... - Andre ???
=====================================

* Species distribution (bird - Phoradendron Californ...)
* Combination of climate & movement
* Scaling (spacial extent & grain) affect ecology
* How does scaling affect the area of distribution?
* What are the ecological implications?
* Approach - Mistletoe system
  * Field work - remote sensing
  * Statistical modeling
* Detect tree tops
* Mesquite affected by mistletoe
* 11,000 mile road trip for ground work
* 22K locations within 300m of highway
* > 20 species from 129 localities
* 60 aerial photographs NAIP (US only) @ 1m resolution
* OO Classification (eCognition 3)
* Maps of the data
* Train model
* Prelimiary results


Searching for Living Fossils: GIS & Niche Modeling - Hannah Owens
=================================================================

* Coelacanths
  * Discoveries
  * Rare & reclusive
  * Two species found in the last 40 years & nothing before that
  * Depth below 100m in caves
* Ecological Niche Modeling
  * Rare species
  * New species - effective with chameleons in Madagascar
* Niche model for the african version
  * Introduce Indian version
  * Attempt to predict other possible locations
* Data & Analysis
  * Localities
  * Data Layers
    * Bathymetry
    * Slope
    * World Ocean Atlas
    * Sediment depth
  * Maxent & GARP
* Partial ROC (Validation of the model)
  * Partition into Northern & Southern data
  * Northern predicted South well, not vice versa
* Niche Viz
  * 5K points in the space
  * Altered variables like ocean depth, sediment levels, oxygen & temperature
  * ^ Based on observation
* Test if it predicts the other species
  * Maxent predicted other in 99%
  * GARP predicted 93%
* Projected across the Indian ocean
  * Heavy along Australian's northern border, also Korea & Japan


Diagnostic the Spatial Structure of Urban Areas of Lawrence using Space Syntax & GIS - Hadi Shateh
==================================================================================================

* Build environment
* Generate information not presently available
* What is space syntax?
  * Set of theories to describe spatial configuration of build environment
  * Conceived in 1970s
  * Axial map
* Traditional approach of drawing & calculating axial map
  * Draw
  * Software analyzes & creates connectivity graph
* Use GIS DBs to develop maps
  * ArcMap
  * Axwoman
* Getting the ready axial maps from GIS databases
  * Kansas highway shapefile - mapcruizin.com
  * Graph, table & scatter
* Measure connectivity, local integration & local depth
* Useful for emergency vehicle routing, traffic & crime
