**List all pods**

	kubectl get po
	
**Create Pod**

	imperative cmd => kubectl create -f firstpod.yaml
	
	declarative cmd => kubectl apply -f firstpod.yaml
	
**Cluster IP**

	kubectl expose pod podname --port=8000 --target-port=80 --name servicename
	
	kubectl get svc

**Node Port**	
	kubectl expose pod myfirstpod --type=NodePort --port=8000 --target-port=80 --name myfirstservice1
		
	
