##postgres
#kubectl apply -f postgres-config.yaml #clear text passwords bad, replacing with secret

kubectl apply -f postgres-secret.yaml #needs to be figured out, preferrably obtained from 1password

kubectl apply -f postgres-pvc-pv.yaml

kubectl apply -f postgres-deployment.yaml

kubectl apply -f postgres-service.yaml

##grafana
kubectl apply -f grafana-clusterip.yaml