##mysql

kubectl create namespace databases

kubectl apply -f /home/ladmin/git/k8s/applications/databases/avrora/mysql-db-creds.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/databases/avrora/mysql-pvc-pv.yaml

kubectl apply -f /home/ladmin/git/k8s/applications/databases/avrora/mysql-deployment.yaml

#kubectl apply -f /home/ladmin/git/k8s/applications/databases/avrora/postgres-service.yaml

