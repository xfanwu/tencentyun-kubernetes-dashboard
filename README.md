How to
======

1. check `~/etc/.kube/config`
1. `kubectl use-context [CONTEXT_NAME]`
1. `kubectl create -f kubernetes-dashboard.yml`
1. `kubectl proxy`
1. visit http://localhost:8001/api/v1/namespaces/kube-system/services/https:kubernetes-dashboard:/proxy/
1. find cluster auth token in **集群信息-密码** field
