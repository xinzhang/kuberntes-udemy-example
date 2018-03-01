###
kubectl create -f helloworld-deploy.yml

kubectl expose deployment helloworld-deployment --type=NodePort

kubectl describe service helloworld-deployment