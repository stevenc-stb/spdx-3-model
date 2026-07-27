SPDX-License-Identifier: Community-Spec-1.0

# AssessmentLevelProtection

## Summary

An assessment class that categorizes protection of an control on an asset.

## Description

Serves as a class for specialized assessments that evaluate the Protection level of control.

## Metadata

- name: AssessmentLevelProtection
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
  - minCount: 1
