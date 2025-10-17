SPDX-License-Identifier: Community-Spec-1.0

# evalutationBasedOn

## Summary

Indicates the specific RequirementVerification instance on which the EvaluationResult is based.

## Description

The evalutationBasedOn property represents the linkage to the particular RequirementVerification that serves as the foundation for generating an EvaluationResult. It connects the evaluation outcome to the defined process or activity that verified the requirement, enabling traceability and validation of the evaluation’s basis. This linkage is critical in systems engineering to ensure that evaluation conclusions clearly reference the verified requirements and their verification methods, supporting auditability, compliance, and rigorous quality control.

## Metadata

- name: evalutationBasedOn
- Nature: ObjectProperty
- Range: RequirementVerification
