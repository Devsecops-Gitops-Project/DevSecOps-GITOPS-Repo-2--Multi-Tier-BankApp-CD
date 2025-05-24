cat <<EOF > cd-repo/docs/argo-cd.md
# ArgoCD Usage
Apply apps:

kubectl apply -f argo/bankapp-application.yaml
kubectl apply -f argo/database-application.yaml
EOF
