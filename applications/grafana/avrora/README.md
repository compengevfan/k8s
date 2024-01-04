##postgres

kubectl apply -f postgres-db-creds.yaml

kubectl apply -f postgres-pvc-pv.yaml

kubectl apply -f postgres-deployment.yaml

kubectl apply -f postgres-service.yaml

##grafana

kubectl apply -f grafana-clusterip.yaml