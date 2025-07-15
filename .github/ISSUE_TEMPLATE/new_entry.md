---
name: New Entry
description: Propose new content or sources for Agrippa's Naval Legacy
title: "[New Entry] <Your Title>"
labels: [new-entry]
body:
  - type: markdown
    attributes:
      value: |
        Thank you for contributing to Agrippa's Naval Legacy! Use this template to propose new content or sources.
  - type: textarea
    id: new-content
    attributes:
      label: Proposed Content
      description: Describe the new content or source (e.g., a new source for Agrippa’s 36 BCE campaign).
      placeholder: "Example: Suggest adding a reference to a naval inscription from Brundisium."
    validations:
      required: true
  - type: textarea
    id: relevance
    attributes:
      label: Relevance
      description: Explain how this contributes to Agrippa’s naval career, life, or propaganda.
      placeholder: "Example: Clarifies Agrippa’s fleet logistics post-Actium."
    validations:
      required: true
  - type: textarea
    id: sources
    attributes:
      label: Sources
      description: Provide citations for your proposal (e.g., primary or secondary sources).
      placeholder: "Example: Inscription cited in Smith (2020), Roman Naval Records."
    validations:
      required: true
---