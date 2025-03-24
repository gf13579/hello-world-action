# Hello World Action

A simple GitHub Action to greet someone by name.

## Inputs

| Input | Description | Required | Default |
|------|-------------|----------|--------|
| name | Name to greet | true | World |

## Example Usage

```yaml
jobs:
  greet:
    runs-on: ubuntu-latest
    steps:
      - uses: gf13579/hello-world-action@v1
        with:
          name: "Alice"

