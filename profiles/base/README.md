When profile-controller image updated, you can run below command to update it in manifest.

```
kustomize edit set image gcr.azk8s.cn/kubeflow-images-public/profile-controller:$NEW_TAG
```
