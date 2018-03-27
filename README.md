# Elasticsearch and Kibana on Kubernetes

### Create the es namespace
```kubectl apply -f ./namespaces/es.yml```

### Create a PersistentVolume
```kubectl apply -f ./pv/pv.yml```

### Create the Elasticsearch PersistentVolumeClaim
```kubectl apply -f ./es/es.pvc.yml```

### Execute the Elasticsearch Deployment
```kubectl apply -f ./es/es.deployment.yml```

### Create the Elasticsearch Service
```kubectl apply -f ./es/es.service.yml```

### Create the Kibana PersistentVolumeClaim
```kubectl apply -f ./kibana/kibana.pvc.yml```

### Execute the Kibana Deployment
```kubectl apply -f ./kibana/kibana.deployment.yml```

### Create the Kibana Service
```kubectl apply -f ./kibana/kibana.service.yml```
