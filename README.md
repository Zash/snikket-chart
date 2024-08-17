# Snikket Helm Chart

## TL;DR

```console
helm install snikket charts/snikket \
    --set domain=chat.example.com \
    --set adminEmail="user@example.com" \
    --set issuer=letsencrypt \
    --set image.tag=stable \
    --set portalSecret="$(pwgen -c 32)"
```

## Dependencies

- [Ingress NGINX](https://kubernetes.github.io/ingress-nginx/)
- [cert-manager](https://cert-manager.io/)
