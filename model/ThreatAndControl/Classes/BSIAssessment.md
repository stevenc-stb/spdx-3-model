SPDX-License-Identifier: Community-Spec-1.0
# BSIAssessment

## Summary

A concrete assessment evaluating the confidentiality, availability, and integrity (BSI triad) levels. 

## Description

Evaluates and assigns security levels to the core BSI. 

## Metadata

- name: BSIAssessment
- SubclassOf: CIAAssessment
- Instantiability: Concrete

## Properties

- bindingCharacter
  - type: Level
  - minCount: 0
  - maxCount: 1
- authenticity
  - type: Level
  - minCount: 0
  - maxCount: 1
- reliability
  - type: Level
  - minCount: 0
  - maxCount: 1 
- nonRepudiation
  - type: Level
  - minCount: 0
  - maxCount: 1 
