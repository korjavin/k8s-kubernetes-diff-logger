This is some yaml files for deploying grafana/kubernetes-diff-logger to k8s

Hardcoded namespace: `gitlab-managed-apps`


Permissions:

`kubectl create clusterrolebinding --user system:serviceaccount:gitlab-managed-apps:default default-sa-admin --clusterrole cluster-admin`
