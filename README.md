# Deploy_SpringBoot_Application

Deploying a Spring Boot application on Kubernetes typically involves creating several Kubernetes resources, including Deployments, Services, and optionally Ingress resources. Here's a sample configuration to deploy a Spring Boot application on Kubernetes:

Dockerize Your Spring Boot Application:
Create k8s Deployment 
Creates svc on K8s to expose the application (as service through type "ClusterIP")
Create Ingress API to get request from outside to POD 

Apply all the yml files. 

Access Your Application:
If you created an Ingress resource, you can access your Spring Boot application via the defined host. If not, you can use a NodePort or LoadBalancer service to access it.
