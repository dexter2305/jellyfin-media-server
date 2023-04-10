# Media Server

Self hosted jellyfin media server over kubernetes cluster. 

# Requirements
- Kubernetes cluster.
- Media path is nix flavored. 

# Installation steps
```bash
git clone git@gitlab.com:diy6523009/media-server.git
cd media_server
kubectl kustomize . 
kubectl apply -k .
```
Kubernetes namespace used is `lab`. 
