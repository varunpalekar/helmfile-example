# helmfile-example
Local test kubernetes cluster deployment using helmfile

Helmfile to cretae following things on kubernetes

1. [metrics-server]
2. [prometheus operator]
3. [log operator]
4. [kong ingress]
5. [loki]

# Test

1. Install https://github.com/nektos/act
2. run `act`

[metrics-server]: https://github.com/helm/charts/tree/master/stable/metrics-server
[prometheus operator]: https://github.com/helm/charts/tree/master/stable/prometheus-operator
[log operator]: https://github.com/banzaicloud/logging-operator
[kong ingress]: https://github.com/Kong/charts/tree/main/charts/kong
[loki]: https://grafana.github.io/loki/charts/
