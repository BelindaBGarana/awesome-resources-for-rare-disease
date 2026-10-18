# Excluded Resources

Resources that were considered but excluded from the main list because they are not specific enough to rare diseases, despite being often tremendously useful. This document helps maintainers track decisions and avoid re-evaluating the same resources.

## General-Purpose Tools & Infrastructure

These are valuable tools but not rare disease-specific:

| Resource | Reason for Exclusion |
|----------|---------------------|
| GitHub | General software development platform |
| BioPortal | General ontology repository |
| OBO Foundry | General ontology registry |
| LinkML | General data modeling language |
| SSSOM | General mapping standard |
| Biolink Model | General biomedical data model |
| KGX | General knowledge graph exchange format |
| ROBOT | General ontology tooling |
| Ontobio | General ontology library |
| OAK (Ontology Access Kit) | General-purpose ontology library; can work with HPO/Mondo but is not RD-specific software |
| pronto | General OBO parser |
| fastobo | General OBO parser |
| InterMine | General data warehouse framework |
| GA4GH | The umbrella genomics standards organization; not RD-specific (the GA4GH Rare Disease Community is included separately) |

## General European Health Data & Research Infrastructures

EU infrastructures that rare disease work builds on (many are named in the EURORDIS European Blueprint for Rare Diseases), but which serve all of health or research:

| Resource | Reason for Exclusion |
|----------|---------------------|
| European Health Data Space (EHDS) | General legal framework for primary and secondary use of health data; no RD-specific provisions |
| MyHealth@EU / eHDSI | General cross-border exchange of patient summaries and prescriptions; carries ORPHAcodes but is not RD-specific |
| EEHRxF | General European EHR exchange format; RD-relevant only via ORPHAcodes in the Patient Summary (the JARDIN RD dataset is included separately) |
| Xt-EHR | General Joint Action on EHR exchange and telemedicine |
| DARWIN EU | EMA's general real-world evidence network; covers all medicines |
| BBMRI-ERIC | General biobanking research infrastructure |
| ECRIN | General clinical trials research infrastructure |
| EATRIS | General translational medicine research infrastructure |

## General Genomics Resources

Useful for genomics broadly, but not rare disease-focused:

| Resource | Reason for Exclusion |
|----------|---------------------|
| Gene Ontology (GO) | Gene function annotations, not disease-specific |
| Ensembl REST API | General genomic annotations |
| VEP | General variant effect prediction |
| SnpEff | General variant annotation |
| dbSNP | General variant database |
| HGNC | Gene nomenclature (useful but not RD-specific) |
| UniProt | Protein database (has disease annotations but primarily protein-focused) |
| CIViC | Cancer-focused variant interpretation; rare cancer syndromes are insufficiently specific to RD |

## General Ontologies & Classification Systems

Ontologies and terminologies that support rare disease work but are not themselves rare disease resources:

| Resource | Reason for Exclusion |
|----------|---------------------|
| Uberon | Cross-species anatomy ontology |
| OBI | Biomedical investigations ontology |
| RO | Relations ontology |
| GENO | Genotype ontology |
| SEPIO | Evidence and provenance ontology |
| MAXO | Medical actions (borderline - may reconsider) |
| SNOMED CT | General clinical terminology for all of healthcare; has Orphanet alignment but is not RD-specific |
| ICD-11 | General WHO disease classification; includes more RD codes than ICD-10 but remains a general-purpose classification |

## Variant Pathogenicity Predictors

These help interpret variants but are general-purpose tools:

| Resource | Reason for Exclusion |
|----------|---------------------|
| CADD | General deleteriousness scores |
| SpliceAI | Splicing predictions |
| REVEL | Missense pathogenicity |
| AlphaMissense | Missense predictions |

## General Data Standards

Standards that are useful for rare disease work but are general-purpose:

| Resource | Reason for Exclusion |
|----------|---------------------|
| FHIR Genomics | General HL7 FHIR resources for genomic data in clinical settings; not RD-specific |
| VRS | GA4GH Variation Representation Specification for computable variant identifiers; general genomics standard |
| HGVS Nomenclature | Standard for describing sequence variants; applies to all genomics, not RD-specific |

## APIs & Data Services

General bioinformatics APIs:

| Resource | Reason for Exclusion |
|----------|---------------------|
| MyGene.info | General gene API |
| MyVariant.info | General variant API |
| PubTator Central | General literature annotation |
| NCBI E-utilities | General NCBI access |
| OLS4 | General ontology lookup service for all biomedical ontologies; not RD-specific |

## Retired Resources

Resources that were on the list but are no longer operational:

| Resource | Reason for Exclusion |
|----------|---------------------|
| NIH GRDR | Global Rare Diseases Patient Registry Data Repository, retired in 2017; succeeded by RaDaR (listed) |

## Notes

- A resource being excluded doesn't mean it's not useful - it means this list focuses specifically on rare disease resources
- If you believe a resource should be reconsidered, please open an issue with rationale for its rare disease relevance
