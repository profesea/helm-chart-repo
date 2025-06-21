# Profesea Helm Chart

This repository contains a Helm chart template for deploying the Profesea application on Kubernetes.

## Usage

1. **Add the repository:**
    ```sh
    helm repo add profesea-helm https://github.com/your-org/helm-chart-repo
    ```

2. **Install the chart:**
    ```sh
    helm install profesea profesea-helm/profesea
    ```

## Configuration

Customize your deployment by editing the `values.yaml` file or passing configuration options via the command line.

## Structure

- `Chart.yaml` – Chart metadata
- `values.yaml` – Default configuration values
- `templates/` – Kubernetes resource templates

## Requirements

- [Helm](https://helm.sh/) 3.x
- Kubernetes cluster

## License

MIT