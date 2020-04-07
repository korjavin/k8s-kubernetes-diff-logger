ns: gitlab-managed-apps
kubectl create clusterrolebinding --user system:serviceaccount:gitlab-managed-apps:default default-sa-admin --clusterrole cluster-admin
