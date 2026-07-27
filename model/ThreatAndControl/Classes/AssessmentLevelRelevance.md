SPDX-License-Identifier: Community-Spec-1.0
# AssessmentLevelRelevance

## Summary

An assessment class that categorizes hreat and Control Relevance Requirement level need on an asset.

## Description

Serves as a class for specialized assessments that evaluate the threat and Control Relevance Requirement level of asset.

## Metadata

- name: AssessmentLevelRelevance
- SubclassOf: ThreatControlAssessment
- Instantiability: Concrete

## Properties

- evaluationData
  - type: DataAssessment
  - minCount: 1
  - maxCount: 1
    
## External properties restrictions

- /ThreatAndControl/ThreatControlAssessment/withThreat
  - maxCount: 0
- /ThreatAndControl/ThreatControlAssessment/withControl
  - maxCount: 0
