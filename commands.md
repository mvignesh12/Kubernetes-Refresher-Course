# 01-Kubectl Basic Commands

## Switch kubectl context to use specific namespace
* kubectl config set-context --current --namespace=vignesh

## Check logs from a pod
* kubectl logs -f myapp-pod
  
    or
  
* kubectl logs -f myapp-pod -n YOUR_NAMESPACE

## Login to a pod
* kubectl exec -it myapp-pod -- bash
  
   or
  
* kubectl exec -it myapp-pod -n YOUR_NAMESPACE -- bash

