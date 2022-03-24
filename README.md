# kustomize-playground

# Command to view the rendered yaml/dry run
### Note: Need to provide path to directory which contains kustomization.yaml 

$ kustomize build base 
or
$ kustomize build dev

# command to apply changes to cluster

$ kubectl apply -k base
$ kubectl apply -k dev



https://kubectl.docs.kubernetes.io/references/kustomize/kustomization/ 
https://kubectl.docs.kubernetes.io/references/kustomize/kustomization/images/

