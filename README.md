# Exivity Helm Charts

This branch contains the Helm repository index for Exivity's forked Bitnami charts.

## Usage

Add this Helm repository:

```bash
helm repo add exivity https://exivity.github.io/bitnami-charts/
helm repo update
```

Search for available charts:

```bash
helm search repo exivity
```

Install a chart:

```bash
helm install my-release exivity/<chart-name>
```

## Available Charts

This repository contains forked versions of Bitnami Helm charts, maintained by Exivity.

For chart source code, visit: https://github.com/exivity/bitnami-charts

---

*This page is automatically maintained by the chart-releaser GitHub Action.*
