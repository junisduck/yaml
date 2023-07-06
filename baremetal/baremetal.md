kubectl create namespaces metallb-system
kubectl apply -f metallb.yaml
kubectl apply -f configmap.yaml

---
kubectl describe -n metallb-system configmap
