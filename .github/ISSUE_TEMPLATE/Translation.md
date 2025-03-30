name: Translation Issue
about: Translation issue or new Language Sup
title: "[Translation]: "
labels: ["Translation",]
assignees: []

body:
  - type: textarea
    id: bug-description
    attributes:
      label: Describe the bug
      description: Please provide a clear and concise description of what the bug is.
      placeholder: Tell us what you see!
    validations:
      required: true
  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: Steps to reproduce
      description: Please provide steps to reproduce the behavior.
      placeholder: 1. Go to... 2. Click on... 3. See error...
    validations:
      required: false
  - type: dropdown
    id: browsers
    attributes:
      label: What browsers are you seeing the problem on?
      options:
        - Chrome
        - Firefox
        - Safari
        - Edge
    validations:
      required: false