#PROMETHEUS
This folder contian Kubernetes manifest for:
- Prometheus (monitoring)

## Deploy Prometheus

sudo mkdir -p /data/prometheus
sudo chmod 777 /data/prometheus

kubectl apply -f prometheus/
