SPDX-License-Identifier: Community-Spec-1.0
# ThreatControlAssessment

## Summary

An abstract assessment that links a target asset to specific threats and/or controls for evaluation.

## Description

Provides a framework for assessing how identified threats and implemented controls affect a specific asset. Acts as a parent class for specialized assessments (e.g., BasicCIAAssessment).

## Metadata

- name: ThreatControlAssessment
- SubclassOf: /Core/Artifact
- Instantiability: Abstract

## Properties

- toAsset
  - type: /Core/Element
  - minCount: 1
- withThreat
  - type: Threat
  - minCount: 0	
- withControl
  - type: Control
  - minCount: 0	
