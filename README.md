```text
Copyright (c) 2020 Actian Corporation
```
## Actian Zen Containers for OpenNESS

This project provides Docker container images of the Actian Zen database and a sample application that are compatible with the [Intel Smart Edge Open Platform](https://www.openness.org/), formerly known as OpenNESS.

To learn more about Actian Zen in Intel Smart Edge Open, please visit the [Actian-Zen](https://github.com/open-ness/edgeapps/tree/master/applications/actian-zen) EdgeApps project.

## Downloads

* [Actian Zen Cloud/Enterprise/Edge Container](https://github.com/ActianCorp/ActianZen-OpenNESS/releases/download/IntelSmartEdgeOpen-1.0/actianzen-15.00.tar.gz)
* [Actian Zen Sample Application Container](https://github.com/ActianCorp/ActianZen-OpenNESS/releases/download/IntelSmartEdgeOpen-1.0/zensample-15.00.tar.gz)

## Container Parameters/Environment Variables

| Parameter | Required | Values | Description |
| --------- | -------- | ------ | ----------- |
| ZEN_ACCEPT_EULA | Yes | Yes | EULA must be accepted to run container |
| ZEN_PRODUCT | No | Cloud, Enterprise, Edge | Specifies Zen product type, Default is Enterprise |
| ZEN_LICENSE | No | *Product license key* | Temporary 30 day trial license is installed if none provided |
