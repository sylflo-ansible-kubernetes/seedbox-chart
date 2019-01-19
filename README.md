# Seedbox

Seedbox is a Kubernetes addon to automate the installation of a seedbox on a Kubernetes
cluster

It will install the following tools:

- deluge
- heimdall
- jackett
- netdata
- plex
- radarr
- seafile
- sonarr

## Prerequisites

- Kubernetes 1.7+

## Installing the Chart


To install the chart with the release name `seedbox`:

```console
$ helm install seedbox  sylflo/seedbox
```

## Uninstalling the Chart

To uninstall/delete the `seedbox` deployment:

```bash
$ helm delete seedbox
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Remarks

If you are using Rancher2 and Ansible you can use this Ansible role it will install and configure the seedbox
https://github.com/sylflo/seedbox-ansible
