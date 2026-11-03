name: Bug report
description: Something does not work as documented
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: >
        Search existing issues first. Do not attach live data directories,
        credentials, or private conversation logs. Sanitize diagnostics.
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Expected and actual behavior.
    validations:
      required: true
  - type: textarea
    id: reproduction
    attributes:
      label: Minimal reproduction
      description: The smallest sequence that triggers the problem.
    validations:
      required: true
  - type: input
    id: versions
    attributes:
      label: Versions
      description: OS, Python, framework/CLI, and pack versions.
    validations:
      required: true
  - type: textarea
    id: logs
    attributes:
      label: Sanitized diagnostics
      description: Optional. Logs or errors with secrets and private data removed.