SPDX-License-Identifier: Community-Spec-1.0

# AIPackage

## Summary

Refers to any unit of content that can be associated with a distribution of
AI software or AI model.

## Description

An AI Package is a specialized type of software Package that includes
code or model that implements artificial intelligence functionalities.

## Metadata

- name: AIPackage
- SubclassOf: /Software/Package
- Instantiability: Concrete

## Properties

- /Core/isoAutomationLevel
  - type: /Core/IsoAutomationLevel
  - minCount: 0
  - maxCount: 1
- autonomyType
  - type: /Core/PresenceType
  - minCount: 0
  - maxCount: 1
- domain
  - type: xsd:string
  - minCount: 0
- energyConsumption
  - type: EnergyConsumption
  - minCount: 0
  - maxCount: 1
- hyperparameter
  - type: /Core/DictionaryEntry
  - minCount: 0
- informationAboutApplication
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- informationAboutTraining
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- limitation
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- metric
  - type: /Core/DictionaryEntry
  - minCount: 0
- metricDecisionThreshold
  - type: /Core/DictionaryEntry
  - minCount: 0
- modelDataPreprocessing
  - type: xsd:string
  - minCount: 0
- modelExplainability
  - type: xsd:string
  - minCount: 0
- safetyRiskAssessment
  - type: SafetyRiskAssessmentType
  - minCount: 0
  - maxCount: 1
- standardCompliance
  - type: xsd:string
  - minCount: 0
- typeOfModel
  - type: xsd:string
  - minCount: 0
- useSensitivePersonalInformation
  - type: /Core/PresenceType
  - minCount: 0
  - maxCount: 1
