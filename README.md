# Helm Agent Repository



## Get started

Add this repository to Helm.

```
helm repo add xm-deamonset https://xmcyber.github.io/xmcyber-helm/
```

Install an xm-deamonset.

```
helm upgrade -i xm-deamonset . --set env.HAXM_CUSTOMER_ID="XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",env.HAXM_SOUTH_SERVER_ADDRESS=s-k8s.haxm.co
```
