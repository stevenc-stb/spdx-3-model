SPDX-License-Identifier: Community-Spec-1.0

# stakeholderPriority

## Summary

The relative importance or urgency assigned to a StakeholderNeed of the stakeholder.

## Description

the stakeholderPriority property enables the ranking and categorization of stakeholder needs to facilitate requirements prioritization and scope management. This property is critical during the Needs Analysis and Requirements Analysis phases, where competing stakeholder needs must be evaluated and balanced against constraints such as cost, schedule, and technical feasibility.

The DefinedType range allows for standardized priority classifications (e.g., MoSCoW: Must, Should, Could, Won't Have; or numerical scales: High, Medium, Low) that can be consistently applied across the project. A stakeholderPriority assignment supports trade-off analysis and ensures that the most critical stakeholder needs are addressed first when resource limitations exist.

This ObjectProperty references a DefinedType to enable formal classification and validation of priority levels, supporting automated analysis and traceability throughout the system life cycle. Priority information may change over time as stakeholder needs evolve or project constraints shift, requiring version control of the stakeholder model.

## Metadata

- name: stakeholderPriority
- Nature: ObjectProperty
- Range: /Core/DefinedType
