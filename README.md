## Santa Barbara Breeding Bird Survey GBIF Upload

[```Citation```](#Citation) / [```Data Definitions```](#data-definitions) / [```Included Resources```](#included-resources) /  [```Data Issues```](#data-issues) / [```Summary```](#summary)

### Description

The tick-interaction-database is a repository for interaction and ecological trait data about ticks. The observations are from the literature and focused on tick hosts, which are important vectors of many arthropod borne pathogens. This is part of the [Terrestrial Parasite Tracker](http://parasitetracker.org/).

This GitHub repository contains scripts that take data from the [Santa Barbara Breeding Bird Survey](https://santabarbaraaudubon.org/santa-barbara-county-breeding-bird-study/) and format in Darwin Core for export to Global Biodiversity Information Facility (GBIF) 

### Citation

### Data Definitions
The definitions of the columns of the speadsheet are described here. If these correspond with Darwin Core they are mapped to those classes. 

* **basisOfRecord** [DWC:BasisOfRecord](http://rs.tdwg.org/dwc/terms/basisOfRecord) : The specific nature of the data record. For observations in the Breeding Bird Survey use HumanObservation.

* identifier = record_number
* occurrenceRemarks = breeding_evidence, comments, observation, nest_species_structure,nest_hgt_meters,sources
* recordedBy = observer
* associatedTaxa = nest_species_structure
* basisOFRecord = HumanObservation
* scientificName = scientific_name
* coordinateUncertaintyInMeters = gps_certainty_meters
* maximumElevationInMeters = elev_meters
* eventDate = 
* remove x, y (from ArcGIS)
* Ignore the time (remove it if possible)


### Included Resources
Data records for this code should be retrieved from the ccber-research google drive folder "Santa Barbara County Breeding Bird Study Data." Name of file may change.

### Data Issues

### Summary
