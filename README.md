# ftp-local

## Kubernetes
```SHELL
kubectl create deployment ftp-deployment --image=alpine --dry-run -o yaml > deployment-ftp.yaml
```

```SHELL
kubectl apply -f deployment-ftp.yaml -n YOUR_NAMESPACE 
```

```SHELL
kubectl exec -it POD_NAME /bin/sh
```

```SHELL
apk add open-ssh
```

```SHELL
sftp username@ip_address/hostname
```


## Docker 
https://hub.docker.com/r/atmoz/sftp
