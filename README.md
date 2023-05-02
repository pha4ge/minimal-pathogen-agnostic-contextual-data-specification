# Minimal Pathogen Agnostic Contextual Data Specification
An international minimal metadata standard for public health and One Health genomic surveillance.
> Table 1: Minimal contextual data requirements for public health and One Health surveillance 

| Field | Ontology ID | Definition | Guidance | Expected Value Type | Benefits | Considerations and Privacy |
|---|---|---|---|---|---|---|
| specimen collector sample ID | GENEPIO:0001123 | The user-defined name for the sample. | Original ID given to the sample at the primary laboratory | Alpha-numeric value | Linkage of sample with genomic, lab and epi data; Identifier tracking and establishing chain of custody; Can be considered Personal Health Identifiable (PHI) information Public facing identifier can be used as replacement when sharing (such as a hash ID) |
| specimen source ID | GENEPIO:0100696 | The identifier assigned to the host or environment from which the specimen was derived (e.g. host subject ID, case ID, environmental site ID) | Provide the identifier for the source of the sample such as the case ID or site ID. | Alpha-numeric value | Allow for deduplication of cases; Traceability | Can be considered Personal Health Identifiable (PHI) information; Public facing identifier can be used as replacement when sharing (such as a hash ID) |
| geo_loc name (country) | GENEPIO:0001181 | The country where the sample was collected. | Use an ontology such as the Gazateer (GAZ). Equivalent to ISO3166-1 Permitted values | Spatio-temporal analysis; International Health Regulations reporting requirements | If event counts in a country are low, perturbation may be required |
| geo_loc name (state/province/region) | GENEPIO:0001185 | The state/province/region where the sample was collected. | Use an ontology such as the Gazateer ontology (GAZ). Equivalent to ISO3166-2 Permitted values | Spatio-temporal analysis | If event counts in a state/province/region are low, perturbation may be required |
| sample collected by | GENEPIO:0001153 | The name of the agency that collected the original sample. | The official organization name should be used (avoid abbreviations, alternate names as much as possible). | Auto complete controlled list | Recognition; Provenance; Contact for follow-up | Care should be taken with regards to potential geographical identification associated with organizational name. |
| sequenced by | GENEPIO:0100416 | The name of the agency that generated the sequence. | The official organization name should be used (avoid abbreviations, alternate names as much as possible). | Auto complete controlled list | Recognition; Provenance; Contact for follow-up | Negligible privacy concerns |
| sequence submitted by | GENEPIO:0001159 | The name of the agency that submitted the sequence to a database. | The official organization name should be used (avoid abbreviations, alternate names as much as possible). | Auto complete controlled list | Recognition; Provenance; Contact for follow-up | Negligible privacy concerns |









