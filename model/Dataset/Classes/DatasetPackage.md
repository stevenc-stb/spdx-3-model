SPDX-License-Identifier: Community-Spec-1.0

# DatasetPackage

## Summary

Refers to any unit of content that can be associated with a distribution of
dataset.

## Description

A Dataset Package is a specialized type of software package that includes
data used for software, hardware, or system training, testing, and calibration,
as well as for reference, archival, or other purposes.

## Metadata

- name: DatasetPackage
- SubclassOf: /Software/Package
- Instantiability: Concrete

## Properties

- /Core/inLanguage
  - type: /Core/LanguageTag
  - minCount: 0
- anonymizationMethodUsed
  - type: xsd:string
  - minCount: 0
- confidentialityLevel
  - type: ConfidentialityLevelType
  - minCount: 0
  - maxCount: 1
- dataCollectionProcess
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- dataPreprocessing
  - type: xsd:string
  - minCount: 0
- datasetAvailability
  - type: DatasetAvailabilityType
  - minCount: 0
  - maxCount: 1
- datasetNoise
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- datasetSize
  - type: xsd:nonNegativeInteger
  - minCount: 0
  - maxCount: 1
- datasetType
  - type: DatasetType
  - minCount: 1
- datasetUpdateMechanism
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- hasSensitivePersonalInformation
  - type: /Core/PresenceType
  - minCount: 0
  - maxCount: 1
- intendedUse
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- knownBias
  - type: xsd:string
  - minCount: 0
- sensor
  - type: /Core/DictionaryEntry
  - minCount: 0
