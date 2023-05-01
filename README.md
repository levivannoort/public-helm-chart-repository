## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to the [documentation](https://helm.sh/docs) to get started with Helm. Once Helm has been set up correctly, add the repo as follows:

```shell
  helm repo add <alias> https://<orgname>.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages. You can then run `helm search repo <alias>` to see the charts.

To install the <chart-name> chart:

```shell
    helm install <chart-name> <alias>/<chart-name>
```

To uninstall the <chart-name> chart:

```shell
    helm delete <chart-name>
```
