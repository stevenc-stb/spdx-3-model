SPDX-License-Identifier: Community-Spec-1.0

# FrequencyMetric

## Summary

A reusable metric class defining the estimated occurrence frequency of an event over a specific time period.

## Description

Combines a categorical frequency level with a specific time span to quantify how often an event, threat, or condition occurs. Designed for broad reuse across security, operational, and compliance assessments.

## Metadata

- name: FrequencyMetric
- Instantiability: Concrete

## Properties

- frequency
  - type: FrequencyCategory
  - minCount: 1
  - maxCount: 1
- timeSpan
  - type: xsd:decimal
  - minCount: 0
  - maxCount: 1

