# jenkins_ci

```bash
cd ~/.kube
kubectl --kubeconfig="k8s-cluster-kubeconfig.yaml" create -f jenkins.yml

kubectl --kubeconfig="k8s-cluster-kubeconfig.yaml" get svc jenkins-svc

kubectl --kubeconfig="k8s-cluster-kubeconfig.yaml" describe svc jenkins-svc

kubectl --kubeconfig="k8s-cluster-kubeconfig.yaml" get ep jenkins-svc

kubectl --kubeconfig="k8s-cluster-kubeconfig.yaml" get rs
```