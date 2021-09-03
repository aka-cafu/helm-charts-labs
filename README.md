# Hello World

This is my first self made chart.

# Usage


## Locally
```bash
$ helm install hello-world ./hello-world --create-namespace lab
```

# From this repo

```bash
$ helm repo add aka-cafu-helm-charts-labs https://aka-cafu.github.io/helm-charts-labs
$ helm repo update
$ helm install hello-world --create-namespace aka-cafu-helm-charts-labs/hello-world -n teste
```

# Update image version

```bash
$ helm upgrade -i --set image.tag=2.0 hello-world ./hello-world -n lab
```