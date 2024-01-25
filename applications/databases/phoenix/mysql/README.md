##mysql

kubectl create namespace databases

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/mysql-db-creds.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/mysql-pvc-pv.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/mysql-deployment.yaml

#kubectl apply -f /home/ladmin/git/k8s/applications/grafana/avrora/postgres-service.yaml

