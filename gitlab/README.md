
## 安装

``` bash
kubectl create ns devops
helm -n devops upgrade --install -f values-gitlab-ce.yaml gitlab ./gitlab
```

## 卸载

``` bash
helm -n devops uninstall gitlab
```
