# Neo

[Traefik](https://traefik.io/) 

## Introduction

This chart bootstraps Neo in Kubernetes ingress controller.

## Installing

### Prerequisites

With the command `helm version`, make sure that you have:
- Helm v3 [installed](https://helm.sh/docs/using_helm/#installing-helm)

Add Neo's chart repository to Helm:

```bash
helm repo add neo https://helm.traefik.io/neo
```

You can update the chart repository by running:

```bash
helm repo update
```

### Deploying Traefik

```bash
helm install neo traefik/neo
```

## Contributing

If you want to contribute to this chart, please read the [Contributing Guide](./CONTRIBUTING.md).
