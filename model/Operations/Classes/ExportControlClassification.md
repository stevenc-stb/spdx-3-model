SPDX-License-Identifier: Community-Spec-1.0

# ExportControlClassification

## Summary

Assement of an Element for export control classification.

## Description

Assement of an Element for export control classification according to the classification schema of one or multiple contries.

## Metadata

- name: ExportControlClassification
- Instantiability: Concrete

## Properties

- exportingCountry
  - type: /Core/Country
  - minCount: 1
  - maxCount: 1
- specification
  - type: /Core/ExternalIdentifier
  - minCount: 1
  - maxCount: 1
- exportClassification
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- weight
  - type: xsd:positiveInteger
  - maxCount: 1
- /Core/comment
  - type: xsd:string
  - maxCount: 1
