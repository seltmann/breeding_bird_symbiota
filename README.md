## Santa Barbara Breeding Bird Survey GBIF Upload

[```Citation```](#Citation) / [```Data Definitions```](#data-definitions) / [```Included Resources```](#included-resources) /  [```Data Issues```](#data-issues) / [```Summary```](#summary)

### Description
This GitHub repository contains scripts that take data from the [Santa Barbara Breeding Bird Survey](https://santabarbaraaudubon.org/santa-barbara-county-breeding-bird-study/) and format in Darwin Core for export to Global Biodiversity Information Facility (GBIF) 

### Citation

### Data Definitions
The definitions of the columns of the spreadsheet are described here. If these correspond with Darwin Core they are mapped to those classes. 

* **occurrenceID** [DWC:occurrenceID](http://rs.tdwg.org/dwc/terms/occurrenceID) : Corresponds to record_number column in the orignial spreadsheet.
* **basisOfRecord** [DWC:BasisOfRecord](http://rs.tdwg.org/dwc/terms/basisOfRecord) : The specific nature of the data record. For observations in the Breeding Bird Survey use HumanObservation. This field was added.
* **country** [DWC:country](http://rs.tdwg.org/dwc/terms/country) : All survey records are from Santa Barbara County, California. This field was added.
* **stateProvince** [DWC:stateProvince](http://rs.tdwg.org/dwc/terms/stateProvince) : All survey records are from Santa Barbara County, California. This field was added.
* **county** [DWC:county](http://rs.tdwg.org/dwc/terms/county) : All survey records are from Santa Barbara County, California. This field was added.
* **decimalLongitude** [DWC:decimalLongitude](http://rs.tdwg.org/dwc/terms/decimalLongitude) : Corresponds to longitude column in orignial spreadsheet.
* **decimalLatitude** [DWC:decimalLatitude](http://rs.tdwg.org/dwc/terms/decimalLatitude) : Corresponds to latitude column in orignial spreadsheet.
* **coordinateUncertaintyInMeters** [DWC:coordinateUncertaintyInMeters](http://rs.tdwg.org/dwc/terms/coordinateUncertaintyInMeters) : Corresponds to gps_certainty_meters column in orignial spreadsheet.
* **maximumElevationInMeters** [DWC:maximumElevationInMeters](http://rs.tdwg.org/dwc/terms/maximumElevationInMeters) : Corresponds to  elev_meters column in orignial spreadsheet.
* **scientificName** [DWC:scientificName](http://rs.tdwg.org/dwc/terms/scientificName) : Corresponds to  elev_meters column in orignial spreadsheet.
* **recordedBy** [DWC:recordedBy](http://rs.tdwg.org/dwc/terms/recordedBy) : Corresponds to observer column in orignial spreadsheet.
* **eventDate** [DWC:eventDate](http://rs.tdwg.org/dwc/terms/eventDate) : Corresponds to to date column in orignial spreadsheet. Date format modified to year-month-day.
* **occurrenceRemarks** [DWC:occurrenceRemarks](http://rs.tdwg.org/dwc/terms/occurrenceRemarks) : Concatination from breeding_evidence, comments, observation, nest_species_structure, nest_hgt_meters, sources in original spreadsheet. 

### Included Resources
Data records for this code should be retrieved from the ccber-research google drive folder "Santa Barbara County Breeding Bird Study Data." The name of the file may change.

### Data Issues
Darwin Core does not support the level behavior detail as found in the Breeding Bird Survey. This information is concatenated and placed in the occurrenceRemarks field, which is functionally a notes field.

### Summary
