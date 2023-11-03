```
helm repo add bitnami https://charts.bitnami.com/bitnami
```

```
helm search repo bitnami
```

```
helm repo update
```

```
helm install bitnami/mysql --generate-name
```

```
helm show chart bitnami/mysql
```

```
helm show all bitnami/mysql
```

Install a release and give a name
```
helm install [NAME] [CHART] [flags]
```

Unstall a release
```
helm unstall [NAME]
```

Check release status
```
helm status [NAME]
```
