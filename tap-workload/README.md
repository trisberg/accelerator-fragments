# tap-workload

To create this fragment use:

```
apiVersion: accelerator.apps.tanzu.vmware.com/v1alpha1
kind: Fragment
metadata:
  name: tap-workload
  namespace: accelerator-system
spec:
  displayName: TAP Workload
  git:
    ref:
      branch: main
    url: https://github.com/trisberg/accelerator-fragments.git
    subPath: tap-workload
```
