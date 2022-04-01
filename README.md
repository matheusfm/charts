# [matheusfm](https://github.com/matheusfm) Helm Charts

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add matheusfm https://matheusfm.dev/charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
matheusfm` to see the charts.

To install the httpbin chart:

```bash
helm install httpbin matheusfm/httpbin
```

To uninstall the chart:

```bash
helm delete httpbin
```

Documentation on each individual chart can be found for

- [httpbin](https://github.com/matheusfm/httpbin-chart)
