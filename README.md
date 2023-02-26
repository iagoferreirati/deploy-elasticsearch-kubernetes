# Create cluster Elasticsearch in Digital Ocean

## Step 1 — Creating a Namespace
```
- kubectl apply -f kube-logging.yaml

## Step 2 - Creating the Headless Service
```
- kubectl apply -f elasticsearch_svc.yaml

## Step 3 - Creating the StatefulSet
```
- kubectl apply -f elasticsearch_statefulset.yaml


## Step 4 - Creating the Kibana Deployment and Service
```
- kubectl apply -f kibana.yaml