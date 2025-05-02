# app-test
testing-app 

## Purpose
Testing application base on **nginx:stable** image. After deploying you will have next resources:
 - deployment
 - hpa
 - configmap
 - service_account
 - service
 - network-policy
 - ingress

### To deploy application into your cluster run
```bash
  helm install app-1 test-app --values test-app/values-app-1.yaml -n app-1 --create-namespace
  helm install app-2 test-app --values test-app/values-app-2.yaml -n app-2 --create-namespace
```
