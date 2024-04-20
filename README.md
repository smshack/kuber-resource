# argoCD 
- https://artifacthub.io/packages/helm/argo/argo-cd?modal=install
```
helm repo add argo https://argoproj.github.io/argo-helm
helm pull argo/argo-cd --version 6.7.12 --untar
```

# jenkins
- https://artifacthub.io/packages/helm/jenkinsci/jenkins
```
helm repo add jenkins https://charts.jenkins.io
helm pull jenkinsci/jenkins --version 5.1.6 --untar
```

# gitlab
- https://artifacthub.io/packages/helm/gitlab/gitlab
```
helm repo add gitlab http://charts.gitlab.io/
helm pull gitlab/gitlab --version 7.11.0 --untar
```

# Mongo
- https://artifacthub.io/packages/helm/bitnami/mongodb
```
helm repo add bitnami https://charts.bitnami.com/bitnami
helm pull bitnami/mongodb --version 15.1.4 --untar

```

# Mysql
- https://artifacthub.io/packages/helm/bitnami/mysql
```
helm repo add bitnami https://charts.bitnami.com/bitnami
helm pull bitnami/mysql --version 10.1.1 --untar

```

# Redis
- https://artifacthub.io/packages/helm/bitnami/redis?modal=install
```
helm repo add bitnami https://charts.bitnami.com/bitnami
helm pull bitnami/redis --version 19.1.2 --untar
```

# airflow
- https://artifacthub.io/packages/helm/apache-airflow/airflow
```
helm repo add apache-airflow https://airflow.apache.org/
helm pull apache-airflow/airflow --version 1.13.1 --untar
```

# grafana
- https://artifacthub.io/packages/helm/grafana/grafana?modal=install
```
helm repo add grafana https://grafana.github.io/helm-charts
helm pull grafana/grafana --version 7.3.9 --untar
```

# prometheus
- https://artifacthub.io/packages/helm/prometheus-community/prometheus?modal=install
```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm pull prometheus-community/prometheus --version 25.19.1 --untar
```

# pinpoint
- https://pinpt.github.io/charts/
```
helm repo add pinpt https://pinpt.github.io/charts
helm install pinpt/oklog
helm install pinpt/mysql
```