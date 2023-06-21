# glueops-pomerium-post-deploy

![Version: 0.2.0-antonio-alpha14](https://img.shields.io/badge/Version-0.2.0--antonio--alpha14-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square)

Helm chart that deploys after the core pomerium ingress controller deployment

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| argocd_domain | string | `"nil"` |  |
| client_id | string | `"nil"` |  |
| client_secret | string | `"nil"` |  |
| dex_domain | string | `"nil"` |  |
| ingress_cert_name | string | `"nil"` |  |
| pomerium_domain | string | `"nil"` |  |
