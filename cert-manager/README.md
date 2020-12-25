## 安装

``` bash
kubectl create ns cert-manager
helm -n cert-manager upgrade --install -f values-cert-manager.yaml cert-manager ./cert-manager
```