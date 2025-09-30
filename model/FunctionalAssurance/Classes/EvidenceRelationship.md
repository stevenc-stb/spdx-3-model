SPDX-License-Identifier: Community-Spec-1.0

# EvidenceRelationship

## Summary

EvidenceRelationship defines the association between pieces of evidence and EvaluationResult.

## Description

EvidenceRelationship defines the association between pieces of evidence and EvaluationResult. This helps to establish traceability and contextual linkage between evidence items, supporting rigorous certification, verification, and audit activities.

## Metadata

- name: EvidenceRelationship
- SubclassOf: /Core/Relationship
- Instantiability: Concrete

## Properties

- evidenceUID
  - type: xsd:anyURI
  - minCount: 0
  - maxCount: 1
- evidenceCategories
  - type: EvidenceType
  - minCount: 0
