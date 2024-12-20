# LB 를 사용할 수 있어야 합니다. 4개의 nginx Pod 가 배포됩니다
## 사용예
helm repo add mynginx https://beomtaek78.github.io/testChart/  
helm install my-nginx-chart mynginx/nginx-chart --version 0.1.0

helm install my-nginx-chart mynginx/nginx-chart --set replicaCount=2 와 같은 방법으로 pod 수를 조절할 수 있습니다  
  
  
## 결과  
kubectl get deploy,svc
