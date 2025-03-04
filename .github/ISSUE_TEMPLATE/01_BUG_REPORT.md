name: Bug report 🐛
description: The library does not work as expected
label: "bug"
body:

- type: checkboxes
  attributes:
  label: Guidelines
  description: Please confirm this is a bug report and not general troubleshooting.
  options:
  - label: I understand that [if I fail to provide all required details, this issue may be closed without review](https://github.com/gravitypdf/querypath/blob/main/.github/CONTRIBUTING.md).
  required: true

- type: textarea
  attributes:
  label: Description of the bug
  validations:
  required: true

- type: input
  attributes:
  label: QueryPath version
  validations:
  required: true

- type: input
  attributes:
  label: PHP Version and environment (server type, cli provider etc., enclosing libraries and their respective versions)
  validations:
  required: true

- type: textarea
  attributes:
  label: Minimal reproducible PHP+HTML snippet to replicate bug
  validations:
  required: true
