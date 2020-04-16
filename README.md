# helm-cert-manager-issuers-letsencrypt

> Helm chart to install a Let's Encrypt cluster issuer on a Kubernetes cluster

[![Build Status](https://github.com/rubenv/helm-cert-manager-issuers-letsencrypt/workflows/Publish/badge.svg)](https://github.com/rubenv/helm-cert-manager-issuers-letsencrypt/actions)

## Usage

```
helm repo add cert-manager-issuers-letsencrypt https://rubenv.github.io/helm-cert-manager-issuers-letsencrypt
helm install cert-manager-issuers-letsencrypt cert-manager-issuers-letsencrypt/cert-manager-issuers-letsencrypt
```

## Configuration

The following table lists the configurable parameters of the cert-manager-issuers-letsencrypt chart and their default values.

Parameter | Description | Default
--- | --- | ---
`dnsSolvers` | DNS solver configuration block | ``

## License

This app is distributed under the [MIT](LICENSE) license.
