SPDX-License-Identifier: Community-Spec-1.0

# DesignRelationship

# Summary

DesignRelationship defines a relationship between design-related elements, capturing their contextual linkage and lifecycle state.

## Description

DesignRelationship models the connections between design artifacts, system elements, or engineering work products. It provides a structured mechanism to track how design decisions, components, or specifications relate to one another and to higher-level requirements or verification activities. The `status` property records the current state of the relationship (e.g., active, superseded, or deprecated), supporting lifecycle management and change control. The `priority` property enables stakeholders to assign relative importance or urgency to specific design linkages, facilitating impact analysis and decision-making. By capturing both the semantic connection and administrative attributes, DesignRelationship ensures clear traceability and supports rigorous design review and validation processes.

## Metadata

- name: DesignRelationship
- SubclassOf: /Core/Relationship
- Instantiability: Concrete

## Properties

- status
  - type: StatusType
  - minCount: 0
- priority
  - type: /Core/DefinedType
  - minCount: 0

