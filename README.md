# Install activemqs

## CD

```bash
kubectl create secret generic -n activemq activemq-secrets --from-literal=ACTIVEMQ_ADMIN_LOGIN='admin' --from-literal=ACTIVEMQ_ADMIN_PASSWORD='hclpdmq24'

helm upgrade activemq charts/activemq --install --namespace activemq --debug
```
