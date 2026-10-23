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

These are to be considered minimum sets as they are based on a limited structured registration in the odontogram, and will be expanded to during the project. These sets can be view in snomedbrowser.org, Norwgian Edition. (Search and choose the set, and view "Medlemar"). Important sources for further expansion of the basic terminology requirement will be 721144007 |General dentistry diagnostic reference set|, which can be viewed in the same browser under the Snomed Derivatives edition. In general these are not intended to be a limitation in the use of terminology, but the intention is to guide early or limited implementation in systems not able to use terminology services. In a good implementation all concepts within scope of Dentistry should be available to Dental healthcare personell, but guided to easy access of the most relevant concepts.

All reference sets can currently be view in the browser or be downloaded from the national release center. DigiDOT will establish and publish FHIR or REST endpoints making these available.

Not all concepts included are yet translated. DigiDOT will contribute to a valid translation of all necessary concepts.

Use of SNOMED CT requires a license which can be obtained via https://mlds.ihtsdotools.org/. There is no license fee for operating and delivering services in Norway.

## Other code systems and value sets

DigiDOTs FHIR profiles can be linked to other code systems or value sets where required either by the FHIR standard or by national regulations. Where no valid code system of value set exists, DigiDOT will produce and publish these as needed within a code system/value set found appropriate.

## Implementation guide

DigiDOT have written an implementation guide based on defined FHIR profiling and terminology. This guide is published on simplifier.net

[View DigiDOT FHIR implementation guide](https://simplifier.net/guide/visual-overview?version=current)
