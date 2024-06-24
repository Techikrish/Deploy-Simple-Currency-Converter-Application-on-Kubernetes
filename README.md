## Prerequisites
#### Minikube
#### Kubectl

1. Clone this repository: .

2. `cd Deploy-Simple-Currency-Converter-Application-on-Kubernetes`

3. `kubectl apply -f deployment.yaml`
4. Verify the deployment:

   ` kubectl get deployments` 
   `kubectl get pods`

5. Apply the service: 

    `kubectl apply -f service.yaml`

6. Verify the service:

    `kubectl get svc`

7. ### Access the Application

8. Get the Minikube IP:

   `minikube ip`

9. Access the application in your browser

`http://<minikube-ip>:30001`
 
