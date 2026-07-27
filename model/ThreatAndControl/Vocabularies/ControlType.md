SPDX-License-Identifier: Community-Spec-1.0

# ControlType

## Summary

Enumeration of Control Type.

## Description

Categorizes security controls based on their functional purpose and timing relative to a threat. It distinguishes between controls designed to prevent occurrence, detect events as they happen, or correct and restore systems after an incident.

## Metadata

- name: ControlType

## Entries

- corrective: Fix the damage caused by a threat.
- detective: Discover a threat that has already occurred (e.g., security audits).
- preventive: Stop the threat from occurring (e.g., firewall, training).
