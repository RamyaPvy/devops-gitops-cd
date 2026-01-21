# devops-gitops-cd

docker->registry->(auto detect)->git update-> ArgoCD deploy to Kubernetes using HElm







\# GitOps CD Pipeline using ArgoCD + Helm



\## Tools Used

\- Docker

\- Docker Hub

\- Kubernetes (Minikube)

\- Helm

\- Argo CD

\- Argo CD Image Updater

\- GitHub



\## Flow

1\. Developer pushes new Docker image to registry

2\. Argo CD Image Updater detects new image

3\. Image tag updated in Git (Helm values.yaml)

4\. Argo CD syncs changes

5\. Kubernetes deploys updated image automatically



