# Generate sample patient cohorts with Synthea

Scripts for orientation and processing of Synthea synthetic patient data  
Output files can be generated by cloning and running synthea [repo](https://github.com/synthetichealth/synthea) or downloaded [directly](https://synthea.mitre.org/downloads)

Only CSV files directly linked to patient electronic health records are processed here (minus billing, hospital, supplier information, FHIR JSON, etc.,)

Preprocessing covers removal of unwanted fields and standardising headers, adding patient age-at-event, filtering to generate sample patient cohorts by criteria and joining records to a single table for mapping and modelling next steps
