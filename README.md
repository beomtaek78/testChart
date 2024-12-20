# LB 를 사용할 수 있어야 합니다
## 사용예
helm repo add mynginx https://beomtaek78.github.io/testChart/  
helm install my-nginx-chart mynginx/nginx-chart --version 0.1.0   
  
  
## 결과  
kubectl get deploy,svc
