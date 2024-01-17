# Cilium with Minikube

## Environment Setup

minikube start \
  --driver=docker \
  --insecure-registry="quay.io" \
  --insecure-registry="registry.k8s.io" \
  --network=minikube \
  --network-plugin=cni \
  --cni=false \

`cilium` 디렉터리에서 `$ kubectl kustomize --enable-helm . | kubectl apply -f - --server-side --force-conflicts`
