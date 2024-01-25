##mysql

kubectl create namespace databases

kubectl apply -f /home/ladmin/git/k8s/applications/databases/phoenix/mysql-db-creds.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/databases/phoenix/mysql-pvc-pv.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/databases/phoenix/mysql-deployment.yaml

#kubectl apply -f /home/ladmin/git/k8s/applications/databases/phoenix/postgres-service.yaml

