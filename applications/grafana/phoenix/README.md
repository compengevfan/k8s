##postgres

kubectl apply -f postgres-db-creds.yaml --namespace=grafana

kubectl apply -f postgres-pvc-pv.yaml --namespace=grafana

kubectl apply -f postgres-deployment.yaml #--namespace=grafana

kubectl apply -f postgres-service.yaml --namespace=grafana

##grafana

kubectl apply -f grafana-clusterip.yaml --namespace=grafana