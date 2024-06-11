# containers.dev
Information about dev containers

List of dev containers can be found at
https://github.com/devcontainers/images/tree/main/src

Dev Container registery can be found at
https://mcr.microsoft.com/en-us/
https://mcr.microsoft.com/en-us/catalog

### Python
https://mcr.microsoft.com/en-us/product/devcontainers/python/tags

```
{
  "image": "mcr.microsoft.com/devcontainers/python:dev-3.12-bookworm",
  "customizations": {
    // Configure properties specific to VS Code.
    "vscode": {
      // Add the IDs of extensions you want installed when the container is created.
      "extensions": ["streetsidesoftware.code-spell-checker", ms-python.python]
    }
  }
}
```

docker pull mcr.microsoft.com/devcontainers/python:dev-3.12-bookworm
#### Sample devcontainer.json - python


### nodejs
docker pull mcr.microsoft.com/devcontainers/typescript-node:dev-18-bullseye

https://containers.dev/guide/dockerfile

#### Sample devcontainer.json
```
{
  "image": "mcr.microsoft.com/devcontainers/typescript-node",
  "forwardPorts": [3000],
  "customizations": {
    // Configure properties specific to VS Code.
    "vscode": {
      // Add the IDs of extensions you want installed when the container is created.
      "extensions": ["streetsidesoftware.code-spell-checker"]
    }
  }
}
```
