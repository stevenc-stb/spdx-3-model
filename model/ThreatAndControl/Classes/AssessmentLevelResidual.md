SPDX-License-Identifier: Community-Spec-1.0
# AssessmentLevelResidual

## Summary

An assessment class that categorizes protection of an Residual risk on an asset.

## Description

Serves as a class for specialized assessments that evaluate the Residual risk level an asset.

## Metadata

- name: AssessmentLevelResidual
- SubclassOf: ThreatControlAssessment
- Instantiability: Concrete

## Properties

- evaluationData
  - type: DataAssessment
  - minCount: 1
  - maxCount: 1
    
## External properties restrictions

- /ThreatAndControl/ThreatControlAssessment/withThreat
  - minCount: 1
