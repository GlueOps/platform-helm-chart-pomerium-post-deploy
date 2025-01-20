# glueops-pomerium-post-deploy

![Version: v0.3.0-rc3](https://img.shields.io/badge/Version-v0.3.0--rc3-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

Helm chart that deploys after the core pomerium ingress controller deployment

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| client_id | string | `"nil"` |  |
| client_secret | string | `"nil"` |  |
| dex_domain | string | `"nil"` |  |
| ingress_cert_name | string | `"nil"` |  |
| pomerium_domain | string | `"nil"` |  |
