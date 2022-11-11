
# Azure Functions Core Tools (azure-functions-core-tools)

Installs the Azure Functions Core Tools along with needed dependencies. Useful for base Dockerfiles that often are missing required install dependencies like gpg.

## Example Usage

```json
"features": {
    "ghcr.io/jlaundry/devcontainers-feature-azure-functions-core-tools/azure-functions-core-tools:1": {
        "version": "latest"
    }
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| version | Select or enter an Azure Functions Core Tools version. (Available versions may vary by Linux distribution.) | string | latest |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/jlaundry/devcontainers-feature-azure-functions-core-tools/blob/main/src/azure-functions-core-tools/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
