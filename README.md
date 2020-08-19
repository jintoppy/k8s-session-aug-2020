# Kubernetes Session

```kubectl apply -f app1/deployment.yaml -n <your_namespace>```
```kubectl apply -f app2/deployment.yaml -n <your_namespace>```

### Few commands
- kubectl get pods -n <your_namespace>
- kubectl get svc -n <your_namespace>
- kubectl get all -n <your_namespace>
- kubectl logs -f <pod_name> -n <your_namespace>
- kubectl exec -it <pod_name> -n <your_namespace> -- /bin/bash

