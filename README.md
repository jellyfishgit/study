# study

## echo adsfasdfasf | base64 --decode   

### helm repo list

### helm repo add 

### helm repo update 

```
helm repo add secrets-store-csi-driver https://raw.githubusercontent.com/kubernetes-sigs/secrets-store-csi-driver/master/charts
helm install -n kube-system csi-secrets-store secrets-store-csi-driver/secrets-store-csi-driver

helm update csi-secrets-store secrets-store-csi-driver/secrets-store-csi-driver -n kube-system --set syscSecret.enabled=true,enableSecretRotation=true
```
