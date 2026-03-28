SPDX-License-Identifier: Community-Spec-1.0

# StakeholderNeed

## Summary

A StakeholderNeed is condition, objective or capability required by a stakeholder to solve a problem.

## Description

A StakeholderNeed represents the high-level intent expressed by stakeholders during the Needs Analysis phase of the life cycle. It defines the problem space or desired capability before it is translated into verifiable system requirements.

This entity captures the natural language expression of the need via the statement property, ensuring the stakeholder's voice is preserved in the model. The stakeholderPriority property allows for the ranking of needs, which is critical for scope management, trade-off analysis, and requirement prioritization. Stakeholder Needs are distinct from System Requirements; while requirements must be technically verifiable, needs express the underlying value or necessity that justifies the system's existence. Traceability from derived requirements back to StakeholderNeeds is essential to ensure alignment with stakeholder expectations with the RelationshipType 'RequirementRefinesStakeholderNeed' 

## Metadata

- name: StakeholderNeed
- SubclassOf: Element
- Instantiability: Concrete

## Properties
 
- statement
  - type: xsd:string
  - minCount: 1
  
- stakeholderPriority
  - type: DefinedType
  - minCount: 0
 
## External properties restrictions

- name
  - minCount: 1
