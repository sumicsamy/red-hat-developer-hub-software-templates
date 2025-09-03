# ${{ values.name }} Database

This repository contains Kubernetes manifests for provisioning a PostgreSQL database.

## Resources
- Deployment: `${{ values.name }}`
- Service: `${{ values.name }}`
- Secret: `${{ values.name }}-db-secret`
- PVC: `${{ values.name }}-pvc`

## OpenShift GitOps
This repo is annotated for auto-discovery by OpenShift GitOps (Argo CD).

ArgoCD App: `${{ values.name }}-db`  
Namespace: `openshift-gitops`
