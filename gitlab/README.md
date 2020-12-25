
## Install
``` bash
kubectl create ns devops
helm -n devops upgrade --install -f values-gitlab-ce.yaml gitlab
```