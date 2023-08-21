Directories:
1.  manifests: K8s Manifest
2.  helm: Helm Package

In order to execute this application:
1. Using manifests:
     kubectl apply -f depl-hello-app.yaml [-n namespace]
     kubectl apply -f svc-hello-app.yaml [-n namespace]

2. Using helm:
     helm install [chart_release] [chart directory]
     helm install hello-app hello-app/ [-n namespace]
   
