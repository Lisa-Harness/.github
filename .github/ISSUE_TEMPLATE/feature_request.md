name: Feature request
description: Propose a change or addition
labels: ["enhancement"]
body:
  - type: textarea
    id: problem
    attributes:
      label: What problem does this solve?
      description: The task or workflow that is harder than it should be.
    validations:
      required: true
  - type: textarea
    id: proposal
    attributes:
      label: Proposed solution
      description: What change you expect. For substantial API or architecture changes, discuss scope before coding.
    validations:
      required: true