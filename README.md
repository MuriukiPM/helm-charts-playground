# Charts

## Getting started

- Install [helm](https://helm.sh/docs/intro/install/). Use the latest stable version

## Vault

> https://github.com/bank-vaults/vault-helm-chart

```sh
helm template vault charts/vault/ -n vault -f charts/vault/values.yaml >  vault.yaml
```
