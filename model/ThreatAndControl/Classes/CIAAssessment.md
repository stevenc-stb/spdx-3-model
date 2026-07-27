SPDX-License-Identifier: Community-Spec-1.0
# CIAAssessment

## Summary

A concrete assessment evaluating the confidentiality, availability, and integrity (CIA triad) levels. 

## Description

Evaluates and assigns security levels to the core CIA triad attributes for a specified asset or threat-control scenario. Extends `AssessmentLevelImpact` to provide structured CIA evaluation.

## Metadata

- name: CIAAssessment
- SubclassOf: DataAssessment
- Instantiability: Concrete

## Properties

- confidentiality
  - type: Level
  - minCount: 1
  - maxCount: 1
- availability
  - type: Level
  - minCount: 1
  - maxCount: 1
- integrity
  - type: Level
  - minCount: 1
  - maxCount: 1 
