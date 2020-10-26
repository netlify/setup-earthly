# setup-earthly

This GitHub Action downloads and installs the latest version of [earthly](https://github.com/earthly/earthly). The version is not currently configurable

## Usage

```yaml
steps:
  - name: Checkout
    uses: actions/checkout@v2
  - name: Setup Earthly
    uses: netlify/setup-earthly@v1
  - name: Use Earthly
    run: earth --version
```
