##postgres

kubectl create namespace grafana

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-db-creds.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-pvc-pv.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-deployment.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-service.yaml

##grafana

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/grafana-clusterip.yaml --namespace=grafana
#Create route