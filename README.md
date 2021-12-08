# bbt.k8s.grafana

Grafana Kubernetes yaml including LDAP and Image Renderer

Fill in the fields specified as XXXX in config-grafana-ldap-toml.yaml according to your company.

if Openshift is used the following command is run
```
oc create configmap cert --from-file=cert.pem -n your-namespace
```

if Kubernetes is used the following command is run
```
kubectl create configmap cert --from-file=cert.pem -n your-namespace
```