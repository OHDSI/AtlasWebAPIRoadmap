# Atlas/WebAPI Roadmap

This repository will provide a place for discussion around the roadmap for next major release of Atlas/WebAPI.

# Functionality for roadmap discussion

The following is a draft list of functionality for discussion in no particular order.

## Java
- What version for support?
- What framework(s) for backend support? Do we stick with an ORM or just code SQL?
- Do we adopt OpenAPI 3.0?
- Do we leverage things like [jhipster](https://www.jhipster.tech/)?

## Integrations

### Strategus

Should provide a representation for any characterization, estimation and prediction study supported by [Strategus](https://github.com/OHDSI/Strategus)

### Arachne

[Arachne](https://github.com/OHDSI/Arachne) will be used for all "generation" tasks done currently in ATLAS. There may be exceptions (i.e. cohort generation of Circe cohorts).

## Security

- New version of WebAPI always require security? Are any endpoints publically available?

### Authentication 

- What methods do we need to support moving forward?

### Authorization

- What authorization scheme do we want to use moving forward?

### User Management

- Role/Permission management for system users

## CDM Source Configuration

- Dedicated "vocabulary" source with PHOEBE recommended tables
- Desire to have source "versions" with individual permissions. 
- Security around data sources? Right now we have encryption for data sources but folks were interested in other ways to secure data sources.
- Source management interface in ATLAS

## Data Sources

- Deprecated in favor of [ARES](https://github.com/OHDSI/Ares).

## Vocabulary Exploration

- Vocabulary exploration/search has different behavior between ATLAS/Athena. How do we unify these experiences?
- How do we potentially share/distribute a SOLR core for use in the vocabulary explortation?

## Concept Sets

- Do we need the "Explore Evidence" tab for negative control generation anymore? Does the CEM connector supersede this?
- Carry over all functionality.

## Cohort Definitions

- Keep all but Reporting tab?

## Characterizations

- Needs gap analysis to see what features are present in ATLAS that could be considered for HADES. Otherwise deprecate and run through Strategus

## Cohort Pathways

- Needs a HADES package for inclusion into Strategus.

## Incidence Rates, Estimation & Prediction

- Needs gap analysis to see what features are present in ATLAS that could be considered for HADES. Otherwise deprecate and run through Strategus

## Other Functionality

### Job Management

- Maybe provided by Arachne?

### Profiles

- Has links to Cohort Sampling functionality in cohort definitions.

### Messages

- I don't know what this and it appears on all design elements?

### Reusables

- Deprecate?

### Tagging

- Continue with tagging?

### Versioning

-- Continue with versioning?

### Internationalization

- Is this still necessary/desired?
