# super-frag

To create this fragment use:


```
apiVersion: accelerator.apps.tanzu.vmware.com/v1alpha1
kind: Fragment
metadata:
  name: super-frag
  namespace: accelerator-system
spec:
  displayName: Super Frag
  git:
    ref:
      branch: main
    url: https://github.com/trisberg/accelerator-fragments.git
    subPath: super-frag
```
