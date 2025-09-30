SPDX-License-Identifier: Community-Spec-1.0

# RequirementVerification

## Summary

Requirementverification class refers to a specific requirement that must be confirmed through testing, inspection, or assessment. 

## Description

Requirementverification class refers to a specific requirement that must be confirmed through testing, inspection, or assessment.
This can include security, operational, functional, or compliance-related needs that must be demonstrably met and documented. 

## Metadata

- name: RequirementVerification
- SubclassOf: /Core/Element
- Instantiability: Concrete

## Properties

- verificationUID
  - type: xsd:anyURI
  - minCount: 0
  - maxCount: 1
- verificationMethod
  - type: VerificationType
  - minCount: 0
- verificationContext
  - type: /Core/RequirementContext
  - minCount: 0
  - maxCount: 1
- verificationPrecondition
  - type: xsd:string
  - minCount: 0
- verificationPostcondition
  - type: xsd:string
  - minCount: 0
- verificationNote
  - type: xsd:string
  - minCount: 0
  - maxCount: 1

