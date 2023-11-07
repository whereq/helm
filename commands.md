```
helm repo add bitnami https://charts.bitnami.com/bitnami
```

```
helm search repo [keyword] [flags]
```

e.g.
```
helm search repo bitnami
# Search for stable release versions matching the keyword "nginx"
$ helm search repo nginx

# Search for release versions matching the keyword "nginx", including pre-release versions
$ helm search repo nginx --devel

# Search for the latest stable release for nginx-ingress with a major version of 1
$ helm search repo nginx-ingress --version ^1.0.0 
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
