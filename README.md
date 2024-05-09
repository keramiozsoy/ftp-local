# ftp-local

## Kubernetes
```SHELL
kubectl create deployment ftp-deployment --image=alpine --dry-run -o yaml > deployment-ftp.yaml
```

```SHELL
kubectl apply -f deployment-ftp.yaml -n YOUR_NAMESPACE 
```


## Docker 
https://hub.docker.com/r/atmoz/sftp
