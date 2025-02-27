SPDX-License-Identifier: Community-Spec-1.0

# Requirements

## Summary

A requirement is a specific condition, capability, or constraint that a product, system, or process must meet.

## Description

A requirement is a specific condition, capability, or constraint that a product, system, or process must meet. Requirements define what needs to be done to achieve a goal, ensuring the correct functionality, performance, and compliance.

## Metadata

- name: Requirements
- SubclassOf: /Core/Artifact
- Instantiability: Concrete

## Properties

- requirementsRationale
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- requirementsUID
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- requirementsStatement 
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- requirementsStatus
  - type: RequirementsStatusType
  - minCount: 0
  - maxCount: 1
- requirementsCatagory
  - type: RequirementsCatagoryType
  - minCount: 0
  - maxCount: 1
- requirementsLevel
  - type: xsd:positiveInteger
  - minCount: 0
  - maxCount: 1
- requirementsCriticality
  - type: xsd:positiveInteger
  - minCount: 0
  - maxCount: 1

