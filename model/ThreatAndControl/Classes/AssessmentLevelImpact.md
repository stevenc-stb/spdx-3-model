SPDX-License-Identifier: Community-Spec-1.0

# AssessmentLevelImpact

## Summary

A concrete assessment class that categorizes the severity or significance of an impact on an asset.

## Description

Serves as a parent class for specialized assessments that evaluate the impact level of threats. Links assessments to their underlying evaluation data for traceability and explicitly focuses on threat-driven impact rather than control effectiveness.

## Metadata

- name: AssessmentLevelImpact
- SubclassOf: ThreatControlAssessment
- Instantiability: Concrete

## Properties

- evaluationData
  - type: DataAssessment
  - minCount: 1
  - maxCount: 1
    
## External properties restrictions

- /ThreatAndControl/ThreatControlAssessment/withControl
  - maxCount: 0
- /ThreatAndControl/ThreatControlAssessment/withThreat
  - minCount: 1
