# tf-test

Deploys flux2 to k8s cluster also adds external Github source (https://github.com/nomercy360/helm-nginx.git) and HelmRelease of simple nginx app to fluxcd

# To run deployment
```
terraform init
```

```
terraform apply
```

Then need to prompt github username and github API token to create new flux-fleet repo
