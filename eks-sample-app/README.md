```
kubectl -n eks-sample-app describe service eks-sample-linux-service
...
kubectl -n eks-sample-app describe pod eks-sample-linux-deployment-65b7669776-m6qxz
kubectl exec -it eks-sample-linux-deployment-65b7669776-m6qxz -n eks-sample-app -- /bin/bash
curl eks-sample-linux-service
cat /etc/resolv.conf
```