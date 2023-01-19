# Helm-charts
## Usage

Helm must be installed to use the charts. Please refer to Helm’s documentation to get started.

Once Helm has been set up correctly, add the repo as follows:

```
helm repo add codebuds https://github.com/agaspar93/Helm
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages. You can then run `helm search repo codebuds` to see the charts.

To install the deno-webserver chart:

```
helm install my-deno-webserver codebuds/deno-webserver
```

To uninstall the chart:

```
helm delete my-deno-webserver 
```
