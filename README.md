## Installation 
helm install [name] ./helmify

## Accessing it
minikube service node-app-service --url

## Updating 
- <b>Update helm templates</b> <br/>
	helm upgrade [name] ./helmify
* <b>Updating image file</b> <br/>
	kubectl set image deployments/node-app node-app=[new image]