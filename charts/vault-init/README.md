# vault-init

This Chart initializes a Vault installation

Simply deploy this chart to your kubernetes cluster and you will initialize Vault in your cluster.

# Usage

Run the following command to install this chart

```sh
helm repo add commbat-charts https://github.com/commbat/helm-charts/raw/master/charts
helm install --name vault-init commbat-charts/vault-init
```

After installing the chart please make sure all Vault pods are running and you have access to the UI.
```
