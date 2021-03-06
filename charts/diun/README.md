# diun

![Version: 0.1.2](https://img.shields.io/badge/Version-0.1.2-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 4.9.0](https://img.shields.io/badge/AppVersion-4.9.0-informational?style=flat-square)

Docker image update notifier

## TL;DR
```console
$ helm repo add nicholaswilde https://nicholaswilde.github.io/helm-charts/
$ helm repo update
$ helm install diun nicholaswilde/diun
```

## Installing the Chart
To install the chart with the release name `diun`:
```console
helm install diun nicholaswilde/diun
```

## Uninstalling the Chart
To uninstall the `diun` deployment:
```console
helm uninstall diun
```
The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

Read through the [values.yaml](https://github.com/nicholaswilde/helm-charts/blob/master/charts/diun/values.yaml)
file. It has several commented out suggested values.

Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`. For example,
```console
helm install diun \
  --set env.TZ="America/New York" \
    nicholaswilde/diun
```

Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart.
For example,
```console
helm install diun nicholaswilde/diun -f values.yaml
```

## Author
This project was started in 2020 by [Nicholas Wilde](http://github.com/nicholaswilde).

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.4.0](https://github.com/norwoodj/helm-docs/releases/v1.4.0)
