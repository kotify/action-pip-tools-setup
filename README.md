# Github Action to setup pip-tools

Versions match pip versions, eg.: `v2023.1` matches pip version `v23.1`.

### Example

```yaml
jobs:
  build:
    steps:
      - uses: actions/checkout@v3
      - uses: kotify/action-pip-tools-setup@v2023.1
```
