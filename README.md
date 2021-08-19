# Helm Example Repository

Ahoy world!  I'm a Helm repository for example charts.

## Get started

Add this repository to Helm.

```
helm repo add helm-examples https://mobiledgex.github.io/helm-examples
```

Install an example.

```
helm install ahoy helm-examples/hello-world
```

## Deploying to the MobiledgeX platform

To deploy the `hello-world` app to the MobiledgeX Platform, use this URL as the image path:
* `https://mobiledgex.github.io/helm-examples:helm-examples/hello-world`

Instructions for deploying Helm apps as available in the [MobiledgeX Developer Portal](https://developers.mobiledgex.com/deployments/supported-apps-types/#helm).
