# k8helloworld

Start minikube

To pull this image:
```
minikube start
```

See/check minikube is unning in virtualbox:
```
virtualbox
```

Verify kubectl and minikube and virtualbox are all working together
```
kubectl get nodes
```

```
docker build -t k8hw:latest .


docker tag k8hw:latest djking/k8hw:latest


docker push djking/k8hw:latest

kubectl create -f k8/hello-world-all.yaml
```
