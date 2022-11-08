# Helm Agent Repository



## Get started

Add this repository to Helm.

```
helm repo add xm-deamonset https://xmcyber.github.io/Agent-Chart/
```

Install an xm-deamonset.

```
helm upgrade -i xm-deamonset . --set env.HAXM_CUSTOMER_ID="2222-bbbb",env.HAXM_SOUTH_SERVER_ADDRESS=s-k8s.haxm.co,env.HAXM_SOUTH_SERVER_PORT="443"
```
