<!--- app-name: WordPress -->

## Hello Rancher Helm Chart

Simple Hello World App

## Prerequisites

- Kubernetes 1.19+
- Helm 3.2.0+

## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm repo add smithcharts https://phsmith.github.io/aula-helm
helm install my-release smithcharts/hello-rancher
```
## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
helm delete my-release
```
