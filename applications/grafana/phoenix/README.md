##postgres

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-db-creds.yaml --namespace=grafana

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-pvc-pv.yaml --namespace=grafana

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-deployment.yaml #--namespace=grafana

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-service.yaml --namespace=grafana

##grafana

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/grafana-clusterip.yaml --namespace=grafana