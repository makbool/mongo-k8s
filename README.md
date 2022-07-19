# mongo-k8s

apply yaml files in the following order
1. mongodb-secret.yaml
2. mongodb-deployment.yaml
3. mongodb-service.yaml
4. mongodb-configmap.yaml
5. mongo-express-deployment.yaml
6. mongo-express-service.yaml

using the command kubectl apply -f <<filename>>

Access mongo express from browser using http://localhost:8081/
