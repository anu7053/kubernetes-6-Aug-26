Creating a simple web application deployment

The first step is to create a Deployment for our webserver that creates a container using the Nginx image.
Copy the below code and save it to a file called nginx-deployment.yaml.


===============================================================
kubectl apply -f nginx-deployment.yaml

kubectl get pods
