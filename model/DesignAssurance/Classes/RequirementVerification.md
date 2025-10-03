SPDX-License-Identifier: Community-Spec-1.0

# RequirementVerification

## Summary

RequirementVerification class describes the method of verification.

## Description

RequirementVerification class describes the method of verification.
The RequirementVerification class describes the inputs to a verification task. 

## Metadata

- name: RequirementVerification
- SubclassOf: /Core/Element
- Instantiability: Concrete

## Properties

- verificationUUID
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
- verifies
  - type: /Core/Requirement
  - minCount: 1
- verificationMethodRationale
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
