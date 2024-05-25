## Instructions

To build the the customized configurations for the respective dev/prod environments, you can run the following in the root directory:
```bash
kustomize build environments/dev > all-dev.yaml
kustomize build environments/prod > all-prod.yaml
```



