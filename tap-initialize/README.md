# java-version

To create this fragment use:


```
apiVersion: accelerator.apps.tanzu.vmware.com/v1alpha1
kind: Fragment
metadata:
  name: tap-initialize
  namespace: accelerator-system
spec:
  displayName: Select Java Version
  git:
    ref:
      branch: main
    url: https://github.com/trisberg/accelerator-fragments.git
    subPath: tap-initialize
```
