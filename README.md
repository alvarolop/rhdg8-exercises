# rhdg8-exercises

```bash
oc process -f rhdg-81.yaml \
  -p CLUSTER_NAMESPACE="user10" \
  -p CLUSTER_NAME="rhdg"  | oc apply -f -
```