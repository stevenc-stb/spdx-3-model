SPDX-License-Identifier: Community-Spec-1.0

# agentPriority

## Summary

The relative importance or urgency assigned to a Need of the agent.

## Description

The agentPriority property enables the ranking and categorization of agent needs to facilitate requirements prioritization and scope management. This property is critical during the Needs Analysis and Requirements Analysis phases, where competing agent needs must be evaluated and balanced against constraints such as cost, schedule, and technical feasibility.

The DefinedType range allows for standardized priority classifications (e.g., MoSCoW: Must, Should, Could, Won't Have; or numerical scales: High, Medium, Low) that can be consistently applied across the project. A agentPriority assignment supports trade-off analysis and ensures that the most critical agent needs are addressed first when resource limitations exist.

This ObjectProperty references a DefinedType to enable formal classification and validation of priority levels, supporting automated analysis and traceability throughout the system life cycle. Priority information may change over time as agent needs evolve or project constraints shift, requiring version control of the stakeholder model.

## Metadata

- name: agentPriority
- Nature: ObjectProperty
- Range: /Core/DefinedType
