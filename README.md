# WordPress on Kubernetes

This project deploys a WordPress site with MySQL backend on Kubernetes using persistent volumes and secrets.

## Features

- WordPress + MySQL on Kubernetes
- Persistent storage for both WordPress and MySQL
- Kubernetes Secrets for secure credentials
- LoadBalancer service for WordPress access

## Screenshots

![Dashboard](screenshots/dashboard.png)
![WordPress](screenshots/wordpress.png)

## How to Use

```bash
kubectl apply -f mysql-secret.yaml
kubectl apply -f persistent-volume.yaml
kubectl apply -f mysql-deployment.yaml
kubectl apply -f mysql-service.yaml
kubectl apply -f wordpress-deployment.yaml
kubectl apply -f wordpress-service.yaml
```

Access WordPress using your cluster IP or LoadBalancer IP.