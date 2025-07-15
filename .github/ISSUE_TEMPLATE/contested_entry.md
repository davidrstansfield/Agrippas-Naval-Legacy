---
name: Contested Entry
description: Challenge or refine existing content in Agrippa's Naval Legacy
title: "[Contested Entry] <Your Title>"
labels: [contested]
body:
  - type: markdown
    attributes:
      value: |
        Thank you for contributing to Agrippa's Naval Legacy! Use this template to challenge or refine existing content.
  - type: textarea
    id: contested-content
    attributes:
      label: Content to Contest
      description: Specify the content you wish to challenge (e.g., a claim in /Naval-Career/actium-to-triumph.md).
      placeholder: "Example: The claim that Agrippa was in Brundisium in late 31 BCE lacks evidence."
    validations:
      required: true
  - type: textarea
    id: evidence
    attributes:
      label: Supporting Evidence
      description: Provide sources or reasoning to support your challenge (e.g., primary sources, archaeological evidence).
      placeholder: "Example: Cassius Dio does not confirm Agrippa’s location in late 31 BCE."
    validations:
      required: true
  - type: textarea
    id: proposed-change
    attributes:
      label: Proposed Change
      description: Suggest how the content should be revised.
      placeholder: "Example: Update to state Agrippa’s location in late 31 BCE is speculative."
    validations:
      required: true
---

# Contested Entry

Thank you for contributing to Agrippa's Naval Legacy! Use this template to challenge or refine existing content.

## Content to Contest
Specify the content you wish to challenge (e.g., a claim in /Naval-Career/actium-to-triumph.md).

*Example*: The claim that Agrippa was in Brundisium in late 31 BCE lacks evidence.

## Supporting Evidence
Provide sources or reasoning to support your challenge (e.g., primary sources, archaeological evidence).

*Example*: Cassius Dio does not confirm Agrippa’s location in late 31 BCE.

## Proposed Change

Suggest how the content should be revised.

*Example*: Update to state Agrippa’s location in late 31 BCE is speculative.