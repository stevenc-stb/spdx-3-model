SPDX-License-Identifier: Community-Spec-1.0

# MaintenanceResult

## Summary

MaintenanceResult is the result of an evaluation. 

## Description

MaintenanceResult is the Result of a EvaluationResult verification, on something that needs to reviewed cyclically

Note: An evaluation with a `inconclusive` EvaluationResultType must have a comment on it.

## Metadata

- name: MaintenanceResult
- SubclassOf: EvaluationResult
- Instantiability: Concrete

## Properties

- evaluationValidUntilTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1

