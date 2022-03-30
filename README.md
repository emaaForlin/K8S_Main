# K8s Setup

1. Apply the initial manifests using `kubectl apply -k apps/InitialManifests`
2. Deploy Argocd with `kubectl apply -k apps/ArgoCD`
3. Apply the `root_app.yaml`

## How to deploy new apps
1. Create all your manifests inside `apps/`
2. Create the argocd app in `argocd/apps`
3. Push all to the git repo