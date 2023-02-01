# istio-examples
 Istio examples 
   - Virtual Service
   - Destination Rule
   - Gateways
   - ServiceEntry
   - Canary,AB https://youtu.be/C9rIJ3LtTKE
   - Circuit Breaker,Retry,Timeout
   - mTLS

 How To Use
   - Install Istio 
     - https://istio.io/latest/docs/setup/getting-started/#download
   - For example canary 
     - kubectl apply -f deployment-ab.yaml 
     - kubectl apply -f gateway.yaml 
     - Port Forward
       -  kubectl port-forward svc/istio-ingressgateway 8080:80 -n istio-system
     - from broswer http://localhost:8080/index/
     
     
