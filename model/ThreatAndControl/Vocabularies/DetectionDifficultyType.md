SPDX-License-Identifier: Community-Spec-1.0

# DetectionDifficultyType

## Summary

Enumeration of detection difficulty levels for threats or security events.

## Description

Categorizes how difficult it is to identify or detect a threat, vulnerability, or security incident in a given operational or technical environment.

## Metadata

- name: DetectionDifficultyType

## Entries

- undetected: The threat or event is virtually impossible to detect with current controls.
- difficult: Detection requires specialized tools, high skill levels, or extensive monitoring.
- moderate: Detection is achievable with standard monitoring and reasonable analyst attention.
- easy: Detection occurs routinely through existing logs, alerts, or visibility mechanisms.
- trivial: Detection is immediate and automatic via built-in system telemetry or basic thresholds.
