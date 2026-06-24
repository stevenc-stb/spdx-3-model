SPDX-License-Identifier: Community-Spec-1.0

# InteractionTemplate

## Summary

A artifact that defines the structure, formatting, and variable placeholders for AI model interactions.

## Description

Represents a parameterized template specification used to construct prompts, payloads, or structured requests for AI models. It supports flexible template instantiation through either a raw text string with placeholder syntax or a structured dictionary of variables and configuration parameters.

## Metadata

- name: InteractionTemplate
- SubclassOf: /Core/Artifact
- Instantiability: Concrete

## Properties

- interactionTemplateString
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- interactionTemplateDictionary
  - type: /Core/DictionaryEntry
  - minCount: 0
