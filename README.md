# test-kubernetes-am
Test deploying ForgeRock AM/DS in Kubernetes.

```
kubectl create -f ds-svc.yml
kubectl create -f am-svc.yml
kubectl create -f ds-deploy.yml
kubectl create -f am-deploy.yml
```