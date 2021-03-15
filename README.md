# argo-minikube-github-action

Run a simple argo test workflow in a minikube Kubernetes installation in github actions
- Argo workflow basics: https://argoproj.github.io/argo-workflows/quick-start/
- Use minikube installed by default on a github runner: https://minikube.sigs.k8s.io/docs/start/
- Create a persistent volume https://kubernetes.io/docs/tasks/configure-pod-container/configure-persistent-volume-storage/ 
- Verify that an output file from an argo workflow step is passed through a mounted volume /mnt/data
- Pass the example ouput as a github artifact
