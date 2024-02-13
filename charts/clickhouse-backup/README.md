###### based on [dpage/pgadmin4]

# pgAdmin 4

[clickhouse-backup](https://github.com/Altinity/clickhouse-backup) A tool for easy ClickHouse backup and restore with support for many cloud and non-cloud storage types.

## TL;DR;

```console
helm repo add ... ...
helm install .../clickhouse-backup
```

## Introduction

This chart create a [clickhouse-backup](https://github.com/Altinity/clickhouse-backup) jobs on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Install the Chart

To install the chart with the release name `my-release`:

```console
$ # Helm 2
helm install --name my-release .../clickhouse-backup
$ # Helm 3
helm install my-release .../clickhouse-backup
```

The command deploys clickhouse-backup jobs on the Kubernetes cluster in the default configuration. The configuration section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstall the Chart

To uninstall/delete the `my-release` deployment:

```console
helm delete --purge my-release
```

The command removes nearly all the Kubernetes components associated with the chart and deletes the release.

## Configuration

[clickhouse-backup]: https://github.com/Altinity/clickhouse-backup
