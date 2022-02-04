# setup-commandbox

Sets up [CommandBox CLI](https://www.ortussolutions.com/products/commandbox) for GitHub Actions.

## Inputs

- `forgeboxAPIKey` - If added to the action, we will seed it in CommandBox for you.
- `version` - The CommandBox version to install, if not passed we use the latest stable.

## Usage

Simple usage:

```yaml
- name: Setup CommandBox
  uses: Ortus-Solutions/setup-commandbox@v1.0.0
```

With ForgeBox Token

```yaml
- name: Setup CommandBox With ForgeBox Key
  uses: Ortus-Solutions/setup-commandbox@v1.0.0
  with:
    forgeboxAPIKey: my-token
```

Install a specific version of CommandBox

```yaml
- name: Setup CommandBox With ForgeBox Key
  uses: Ortus-Solutions/setup-commandbox@v1.0.0
  with:
    version: 5.0.0
```
