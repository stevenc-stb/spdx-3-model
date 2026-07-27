SPDX-License-Identifier: Community-Spec-1.0
# AssessmentDetectability

## Summary

A concrete assessment class that evaluates the likelihood and speed of detecting a threat or security event. 

## Description

Serves as a specialized assessment that measures how easily and quickly a threat, vulnerability, or security incident can be identified by monitoring systems, security teams, or automated controls. Extends `ThreatControlAssessment` to provide structured detectability metrics, including a categorical difficulty rating and a quantitative mean time to detect (MTTD).

## Metadata

- name: AssessmentDetectability
- SubclassOf: ThreatControlAssessment
- Instantiability: Concrete

## Properties
- detectionDifficulty
  - type: DetectionDifficultyType
  - minCount: 0
  - maxCount: 1
- meanTimeToDetect
  - type: xsd:decimal
  - minCount: 0
  - maxCount: 1
    
## External properties restrictions

- /ThreatAndControl/ThreatControlAssessment/withThreat
  - minCount: 1
