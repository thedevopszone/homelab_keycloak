# homelab_keycloak


## Links

https://github.com/bitnami/charts/tree/main/bitnami/keycloak

## Install

```
kubectl create ns keycloak
helm install keycloak oci://registry-1.docker.io/bitnamicharts/keycloak
```

## Login

Default Login is: user and the Password can be extracted from the secret
