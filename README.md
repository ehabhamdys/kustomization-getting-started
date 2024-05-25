## Instructions

To build the the customized configurations for the respective dev/prod environments, you can run the following in the root directory:
```bash
kustomize build environments/dev > all-dev.yaml
kustomize build environments/prod > all-prod.yaml
```


> :warning: This will fail since the environment overlays are in the same directory as the base configurations according to this issue: https://github.com/kubernetes-sigs/kustomize/issues/851#issuecomment-470285817




