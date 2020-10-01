# k8s-demos
Demo YAML files for creating K8s resources
pod-3000 creates a pod based on dockerhub container image taupoali/docker-node-demo
rc-3000 creates a replication controller based on same image
The container image references has a listener on TCP:3000 which simply returns "Hello World"
