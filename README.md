# Install activemqs

## CD

```bash
<<<<<<< HEAD
kubectl create secret generic -n activemq activemq-secrets --from-literal=ACTIVEMQ_ADMIN_LOGIN='admin' --from-literal=ACTIVEMQ_ADMIN_PASSWORD='hclpdmq24'

helm upgrade activemq charts/doit/activemq --install --namespace activemq --debug
=======
kubectl create ns doit-xxx

kubectl create secret generic -n ${namespace} ${name}-secrets

kubectl create secret docker-registry registry-gitlab --docker-server="registry-gitlab.pcnt.io" --docker-username="registry-gitlab" --docker-password="xxxxxxxxx" -n doit-xxx

helm upgrade ${name} charts/onscore/microservice --install --namespace ${namespace} -f devops/onscore/env/values.yaml -f devops/onscore/env/values.${env}.yaml -f devops/onscore/env/${name}/values.yaml -f devops/onscore/env/${name}/values.${env}.yaml  --debug
>>>>>>> 8107b2e99d0e926f9d7120aabb80b7c2b8f57e6c
```
