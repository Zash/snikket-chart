# Snikket Helm Chart

```console
helm install snikket snikket \
    --set domain=chat.example.com \
    --set adminEmail="user@example.com" \
    --set issuer=letsencrypt \
    --set image.tag=stable \
    --set portalSecret="$(pwgen -c 32)"
```
