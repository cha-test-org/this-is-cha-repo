---
name: WOWOW template
about: this is a wow template
title: 'WOW?'
labels: ''
assignees: ''
body:
- type: markdown
  attributes:
    value: "## Welcome!"
- type: markdown
  attributes:
    value: |
      Thanks for taking the time to fill out this bug! If you need real-time help, join us on Discord.
- type: dropdown
  id: issuetypes
  attributes:
    label: IssueTypes?
    options:
      - IssueTypes1
      - IssueTypes2
      - IssueTypes3
      - IssueTypes4
  validations:
    required: true

---

