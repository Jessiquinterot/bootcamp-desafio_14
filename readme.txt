# Kubernetes NGINX Deployment

Este repositorio contiene los archivos de manifiesto para desplegar una instancia de NGINX en un clúster de Kubernetes.

## Archivos

- `deployment.yaml`: Define el despliegue de NGINX con 3 réplicas.
- `service.yaml`: Expone el servicio NGINX usando un LoadBalancer.

## Instrucciones

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio

2. Aplica los archivos de manifiesto:
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

3. Obtén la URL del servicio:
minikube service nginx-service --url

4. en mi caso: http://127.0.0.1:62391


