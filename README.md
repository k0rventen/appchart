# appchart

A simple helm chart for deploying simple deployments to k8s.

tl;dr:
```
apps:
  - name: simple-echo
    image: traefik/whoami@sha256:200689790a0a0ea48ca45992e0450bc26ccab5307375b41c84dfc4f2475937ab
    service: 80
    ingress:
      domain: echo.domain.com
```

then deploy with:

```
<wip>
```