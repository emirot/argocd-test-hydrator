# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/emirot/argocd-test-hydrator
# cd into the cloned directory
git checkout 0d288ebfe955eb8b9c7a2b049f47fac77e4951e0
helm template . --name-template my-release --values ./hello-world/values.yaml --include-crds
```
