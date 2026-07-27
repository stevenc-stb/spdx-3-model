SPDX-License-Identifier: Community-Spec-1.0

# AssessmentLikelihood

## Summary

An assessment assessment class that evaluates the likelihood of a threat materializing on an asset.

## Description

Serves as a specialized assessment that evaluates the residual risk level of an asset by analyzing attack frequency metrics and feasibility. Extends `ThreatControlAssessment` to provide structured likelihood metrics.

## Metadata

- name: AssessmentLikelihood
- SubclassOf: ThreatControlAssessment
- Instantiability: Concrete

## Properties

- attackFrequencyAttempted
  - type: FrequencyMetric
  - minCount: 1
  - maxCount: 1
- attackFeasibility
  - type: AttackFeasibilityType
  - minCount: 1
  - maxCount: 1
    
## External properties restrictions

- /ThreatAndControl/ThreatControlAssessment/withThreat
  - minCount: 1
