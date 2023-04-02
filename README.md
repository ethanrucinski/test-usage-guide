# Test hinting action

<!-- action-docs-description -->
## Description

An action to test hinting
<!-- action-docs-description -->

<!-- action-docs-usage project="ethanrucinski/test-hinting-action" version="v1" -->
## Usage

```yaml
- uses: ethanrucinski/test-hinting-action@v1
  with:
    numberA:
    # The first number to provide
    #
    # Required: true

    numberB:
    # The second number to provide
    #
    # Required: false
    # Default: 0
```
<!-- action-docs-usage project="ethanrucinski/test-hinting-action" version="v1" -->

<!-- action-docs-inputs -->
## Inputs

| parameter | description | required | default |
| --- | --- | --- | --- |
| numberA | The first number to provide | `true` |  |
| numberB | The second number to provide | `false` | 0 |
<!-- action-docs-inputs -->

<!-- action-docs-outputs -->
## Outputs

| parameter | description |
| --- | --- |
| sum | The sum of the inputs |
<!-- action-docs-outputs -->

<!-- action-docs-runs -->
## Runs

This action is a `composite` action.
<!-- action-docs-runs -->
