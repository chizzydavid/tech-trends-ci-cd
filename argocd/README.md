SETTING UP ARGOCD

# kubectl create namespace argocd

# kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

# kubectl get all -n argocd  

# kubectl apply -n argocd -f argocd/argocd-server-nodeport.yaml

# kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d

Create ArgoCd Applications
#  kubectl apply -f helm-techtrends-staging.yaml 
#  kubectl apply -f helm-techtrends-prod.yaml 

