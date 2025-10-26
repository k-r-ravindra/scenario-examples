Your pod is lost! Let us define a controller that can take care of your pod 

Run

`kubectl create deployment nginx-ravindra --image nginx --replicas 1 --port 80`

Check if the deployment is successful

`kubectl get deployments`

Now try deleting the pod 

`kubectl get pods`

`kubectl delete pod nginx-xxxxxx`
