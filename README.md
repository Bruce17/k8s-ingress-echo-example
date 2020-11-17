# K8s/K3s Ingress echo server example

K8s ingress example using echo server

Extended example off [Kubernetes Ingress with Nginx Example](https://matthewpalmer.net/kubernetes-app-developer/articles/kubernetes-ingress-guide-nginx-example.html). Created new Pod files using ARM based images to run them on a [K3s](https://k3s.io/) cluster on Raspberry PIs.

It does not matter if you are using Nginx or Traefik as Ingress controller. My cluster is running Traefik and the example works fine.
