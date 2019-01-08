## docker-conainer

docker run --env-file sample_env_file -it -d -p 9103:9103 rakeshpatnaik/prometheus-openstack-exporter:v0.2

## k8s-pod

kubectl create ns monitoring
kubectl apply -f openstack-exporter.yaml

