name: 🐛 Bug Report
description: Report a bug to help us improve.
labels: ["bug", "triage"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: textarea
    id: reproduction
    attributes:
      label: Summary & Steps to Reproduce
      placeholder: |
        1. Go to '...'
        2. Click on '....'
        3. See error
    validations:
      required: true
  - type: textarea
    id: behavior
    attributes:
      label: Expected vs Actual Behavior
      placeholder: |
        I expected it to do X, but it did Y.
    validations:
      required: true
  - type: textarea
    id: environment
    attributes:
      label: Environment Info
      placeholder: |
        - OS: [e.g. Windows 11]
        - Version: [e.g. 1.2.3]
        - Browser: [e.g. Chrome 120]
    validations:
      required: true
  - type: checkboxes
    id: checklists
    attributes:
      label: Checklists
      options:
        - label: I have searched existing issues.
          required: true
        - label: I have reproduced this in the latest version.
          required: true
