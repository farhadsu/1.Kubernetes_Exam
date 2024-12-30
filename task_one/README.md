Apply the configuration using kubectl:

kubectl apply -f ConfigMap.yaml

Verify the resources

kubectl get configmap my-config
kubectl get deployment echo-name-deployment
kubectl logs -l app=echo-name

