# inp-spring-boot-api

Assignment 1 answer. I used some of the default values for argocd (project name, k8s cluster adress). In real world this should be changed. 

If you modify the cluster urls and have the names added to argocd + uncomment the args/command section in `chart/templates/deployment.yaml` file after `kubectl apply -f argocd/applicationset.yaml -n argocd` this should deploy. At least it does on my lab (a.k.a. "u mnie działa ;)" )