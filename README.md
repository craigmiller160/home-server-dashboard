# Home Server Dashboard

Exposes the Kubernetes Dashboard for the cluster.

## Repository

```bash
helm repo add prod_nexus https://nexus-craigmiller160.ddns.net/repository/helm-private
```

## Getting the Access Token

After the first deployment, run this command on the server to get the access token. Store it in the 1Password Kubernetes Dashboard Token.

```bash
sudo microk8s kubectl create token default
```