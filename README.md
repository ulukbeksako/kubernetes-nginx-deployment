# Kubernetes NGINX Deployment

This project demonstrates deploying an NGINX web server application in Kubernetes using Deployments, Services, and ConfigMaps.

## Files
- `deployment.yaml`: Defines the NGINX Deployment with 3 replicas.
- `service.yaml`: Exposes the Deployment as a LoadBalancer Service.
- `configmap.yaml`: Provides configuration for environment variables.

## Steps to Deploy
1. Apply the ConfigMap:
   kubectl apply -f configmap.yaml
2.	Apply the Deployment:
   kubectl apply -f deployment.yaml
3. Apply the Service:
   kubectl apply -f service.yaml
4.	Verify the Deployment:
   kubectl get deployments
5. Check the Service:
   kubectl get svc
Finish

   