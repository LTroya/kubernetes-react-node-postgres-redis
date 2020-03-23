# Kubernetes

In order to run the project ingress controller needs to be 
configured. Here is the docs

https://github.com/kubernetes/ingress-nginx

After configured the ingress controller, create
the secret for the database, like so:

```
kubectl create secret generic pgpassword --from-literal PGPASSWORD=YOUR_VALUE_GOES_HERE
``` 