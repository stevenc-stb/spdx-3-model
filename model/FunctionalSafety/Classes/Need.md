SPDX-License-Identifier: Community-Spec-1.0

# Need

## Summary

A Need is condition, objective or capability desired by a Role.

## Description

A Need represents the high-level intent of a Role during the Needs Analysis phase of the life cycle. It defines the problem space or desired capability before it is translated into verifiable system requirements.

This entity captures the natural language expression of the need via the statement property, ensuring the Role's voice is preserved in the model. The AgentPriority property allows for the ranking of needs, which is critical for scope management, trade-off analysis, and requirement prioritization. RoleNeeds are distinct from System Requirements; while requirements must be technically verifiable, needs express the underlying value or necessity that justifies the system's existence and are **validated** by the Agent that is qualified to fulfill the Role. Traceability from derived requirements back to Needs is essential to ensure alignment with role expectations with the RelationshipType 'satisfies'.

## Metadata

- name: Need
- SubclassOf: /Core/Element
- Instantiability: Concrete

## Properties

- statement
  - type: xsd:string
  - minCount: 1
- rolePriority
  - type: /Core/DefinedType
  - minCount: 0

## External properties restrictions

- /Core/Element/name
  - minCount: 1
