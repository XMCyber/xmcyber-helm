# Helm Agent Repository



## Get started

Add this repository to Helm.

```
helm repo add xm-deamonset https://github.xmcyber.com/pages/XM/Agent-Chart/
```

Install an example.

```
helm upgrade -i xm-deamonset . --set env.HAXM_CUSTOMER_ID="2222-bbbb",env.HAXM_SOUTH_SERVER_ADDRESS=s-k8s.haxm.co,env.HAXM_SOUTH_SERVER_PORT="443"
```
