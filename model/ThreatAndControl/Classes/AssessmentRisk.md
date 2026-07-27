SPDX-License-Identifier: Community-Spec-1.0
# AssessmentRisk

## Summary

An assessment class that categorizes risk on an asset.

## Description

Serves as a class for specialized assessments that evaluate risk level an asset.

## Metadata

- name: AssessmentRisk
- SubclassOf: ThreatControlAssessment
- Instantiability: Concrete

## Properties

- estimatedMeanTimeToContain
  - type: xsd:decimal
  - minCount: 0
  - maxCount: 1
- assetRiskRelevance
  - type: AssessmentLevelRelevance
  - minCount: 1
- riskLikelihood
  - type: AssessmentLikelihood
  - minCount: 1
- riskCoreValuesImpaired
  - type: AssessmentLevelImpact
  - minCount: 1
- riskEffects
  - type: AssessmentLevelResidual
  - minCount: 1
- riskDetectability
  - type: AssessmentDetectability
  - minCount: 0
- riskWithoutAdditionalControl
  - type: Level
  - minCount: 1
   
## External properties restrictions

- /ThreatAndControl/ThreatControlAssessment/withThreat
  - minCount: 1
