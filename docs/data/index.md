# Profiling and terminology

This section provides references to the FHIR profiles, Snomed terminology and other data definitions used in DigiDOT interfaces.

## FHIR profiling

DigiDOT is designed based on FHIR profiles developed based on existing national / international standards. These profiles are published on Simplifier.net.

[View DigiDOT profiles on Simplifier.net](https://simplifier.net/DigiDOT-Norwegian-Public-Dental-Service/~introduction)

## Terminology

DigiDOT uses SNOMED CT as terminology reference for all clinical information. This includes:
- Clinical findings and diagnosis
- Procedures
- Observations
- Anatomy

This list is not exhaustive.

DigiDOT will base terminology reference on the Norwegian extension of SNOMED CT including the following derivatives:
- 598071000202105 |tannhelsetjenestens kjerneliste for funn og diagnose enkelt referansesett|
- 598061000202101 |tannhelsetjenestens kjerneliste for prosedyrer enkelt referansesett|
- 598051000202104 |tannhelsetjenestens kjerneliste for tenner enkelt referansesett|
- 598041000202102 |tannhelsetjenestens kjerneliste for overflater og regioner enkelt referansesett|

These are to be considered minimum sets and will be expanded during the project.

Not all concepts included are yet translated. DigiDOT will contribute to a valid translation of all necessary concepts.

SNOMED CT kan be obtained by requesting a license via https://mlds.ihtsdotools.org/. There are no license fee for operating and delivering services in Norway.

## Other code systems and value sets

DigiDOTs FHIR profiles can be linked to other code systems or value sets where required either by the FHIR standard or by national regulations. Where no valid code system of value set exists, DigiDOT will produce and publish these as needed within a code system/value set found appropriate.

## Implementation guide

DigiDOT have written an implementation guide based on defined FHIR profiling and terminology. This guide is published on simplifier.net

[View DigiDOT FHIR implementation guide](https://simplifier.net/guide/visual-overview?version=current)
