## BASIC K8S Commands
# Get all the pods
kubectl get pods
# Run a Bash shell in dedicated Pod
kubectl exec -it pod [pod name] sh
# Get all/print out pod's logs
kubectl logs pod [pod name]
# Delete the Pod
kubectl delete pod [pod name]
# Tell K8s to process the config gile
kubectl apply -f [config file name]
# Print out some information about the running pods
kubectl describe pod [pod name]
# Alias k8s "kubectl" to "k"

## K8S DEPLOYMENT Commands 
# List of k8s deployments
kubectl get deployments
# Print out details about specific deployments
kubectl describe deployment [depl name]
# Create a deployment out of config file
kubectl apply -f [config file name]
# Delete a k8s deployment
kubectl delete deployment [depl name]

