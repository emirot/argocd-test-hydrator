# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/emirot/argocd-test-hydrator
# cd into the cloned directory
git checkout be3def5bc507636a20a8eb773a58468b4fb9c160
kustomize build ./overlays/dev
```
