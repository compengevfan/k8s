##postgres

./kubectl create namespace grafana

./kubectl apply -f /home/ladmin/git/k8s/applications/grafana/phoenix/postgres-db-creds.yaml

./kubectl apply -f /home/ladmin/git/k8s/applications/grafana/phoenix/postgres-pvc-pv.yaml

./kubectl apply -f /home/ladmin/git/k8s/applications/grafana/phoenix/postgres-deployment.yaml

./kubectl apply -f /home/ladmin/git/k8s/applications/grafana/phoenix/postgres-service.yaml

##grafana

./kubectl apply -f /home/ladmin/git/k8s/applications/grafana/phoenix/grafana-clusterip.yaml --namespace=grafana
#Create route