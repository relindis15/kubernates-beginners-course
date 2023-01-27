to run a pod

```bash
    kubectl run <pod-name> --image=nginx

    kubectl run nginx --image=nginx
```

to get all pods

```bash
    kubectl get pods
``` 

delete a pod

```bash
    kubectl delete pod <pod-name>
```

create a pod from yaml

```bash
    kubectl create -f <file-name>
```