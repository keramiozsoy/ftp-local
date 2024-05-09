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
telnet ip_address:22
```

```SHELL
apk add open-ssh
```

```SHELL
sftp username@ip_address/hostname
```


```SHELL

ssh -oHostKeyAlgorithms=+ssh-dss user@host

```

## Docker 
https://hub.docker.com/r/atmoz/sftp
