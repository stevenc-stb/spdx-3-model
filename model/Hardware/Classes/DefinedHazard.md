SPDX-License-Identifier: Community-Spec-1.0

# DefinedHazard

## Summary

Defined hazards refer to specific, recognized risks or dangers that are identified and categorized based on their potential to cause harm to people, property, the environment or itself.

## Description

These hazards are typically identified through risk assessments, safety regulations, or industry standards, and they often have established protocols or guidelines to mitigate or manage their impact. Examples of standards include: IEC 61508, ISO 26262, DO-178C, IEC 60601, ISO 13849 and others.

## Metadata

- name: DefinedHazard
- Instantiability: Concrete

## Properties

- hazardType
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- definitionSource
  - type: /Core/StandardAndSpecifications
  - minCount: 1
  - maxCount: 1
  
