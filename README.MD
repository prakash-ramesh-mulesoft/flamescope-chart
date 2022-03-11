Netflix - Flamescope/Flamechart opensource contribution
https://github.com/Netflix/flamescope

This helps in a great deal to visualize the stacktrace to identify performance bottlenecks

This repo is to setup the same using helm on a k8s environment

Pre-requisites
1) Running Kubernetes Environment (Any k8s environment. On local- minikube/kind/docker etc.)
2) helm 2

This deploys flamescope as kubernetes deployment with  https://hub.docker.com/r/prakashramesh/flamescope


