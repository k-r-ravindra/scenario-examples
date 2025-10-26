Let us try to see available services in your application

List the services with 

`kubectl get svc`

Types of Services:

`Cluster IP`: Only available within cluster for other pods
`NodePort`: Expose a port on the server IP to expose the pod
`LoadBalancer`: Expose on a cloud loadbalancer (Needs cloud integration)

Now let us expose our deployment port

`kubectl expose deployment nginx-ravindra --type=NodePort`

Once you have a port, open the menu on top right and use the port number to visit your service.