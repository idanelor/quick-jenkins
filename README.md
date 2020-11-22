# quick-jenkins

This is an easy yaml file to get a simple Jenkins instance up and running.
1. Install Minikube
2. Run ```kubectl apply -f jenkins.yaml```
3. Run ```minikube service jenkins```
4. To pull admin password you can do the following:
  ```kubectl get pods```
  ```kubectl logs <JENKINS CONTAINER NAME>```
