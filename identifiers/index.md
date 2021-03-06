---
permalink: /identifiers/
layout: default
title: FAIR term identifiers
---

# FAIR term identifiers

Examples of individual items from some vocabularies in the [persistent domains](../domains), which illustrate 

**Rule 5.** Design an identifier scheme and pattern.  

- **‘metres per second’** is defined in four different FAIR vocabularies, two of which use term-based local-ids, while two are opaque

  - [http://sweetontology.net/reprSciUnits/**meterPerSecond**](http://sweetontology.net/reprSciUnits/meterPerSecond)
  - [http://qudt.org/vocab/unit/**M-PER-SEC**](http://qudt.org/vocab/unit/M-PER-SEC)
  - [http://purl.obolibrary.org/obo/**UO_0000094**](http://purl.obolibrary.org/obo/UO_0000094)
  - [http://vocab.nerc.ac.uk/collection/P06/current/**UVAA**/](http://vocab.nerc.ac.uk/collection/P06/current/UVAA/)

- [ANZ Soil Vocabularies](http://registry.it.csiro.au/def/soil/au/asls) use local-ids that concatenate a collection-name and item-code 

  - [http://anzsoil.org/def/au/asls/landform/**morphological-type-H**](http://anzsoil.org/def/au/asls/landform/morphological-type-H)
  - [http://anzsoil.org/def/au/asls/soil-profile/**field-texture-CS**](http://anzsoil.org/def/au/asls/soil-profile/field-texture-CS)

- The FAIR [Geological Timescale prepared by GeoSciML](https://github.com/CGI-IUGS/timescale-data), and the [place-classification vocabulary](http://pid.geoscience.gov.au/def/voc/ga/PlaceType) used in the Australian public sector, use the familiar name of the item as the local-id 

  - [http://resource.geosciml.org/classifier/ics/ischart/**Phanerozoic**](http://resource.geosciml.org/classifier/ics/ischart/Phanerozoic)
  - [http://pid.geoscience.gov.au/def/voc/ga/PlaceType/**MOUNTAIN**](http://pid.geoscience.gov.au/def/voc/ga/PlaceType/MOUNTAIN)

These IRIs are actionable, following 

**Rule 9.** Make the IRIs resolve - address vocabulary Accessibility.  

