How to use
  - kubectl apply -f deployment-ab.yaml
  - kubectl apply -f gateway.yaml
  - Port Forward
      - kubectl port-forward svc/istio-ingressgateway 8080:80 -n istio-system
  - from broswer http://localhost:8080/index/
