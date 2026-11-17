## Spring project for K8s_for_demo project

* This project serves as input to to demo kubernetes project called K8s_for_demo with 2 pods, traefik and load balancer
* This project has endpoint /hello and test cases for the same

### Trying git-worlflows and git actions
* Also used to enforce PR-Merge only if two git workflows-build and test, pass 
* Added 2nd workflow to build and push image of spring on docker hub
* Added 3rd workflow to update manifest code(image tag) in infrastructure code in K8s_for_demo which inturn triggers ArgoCD to auto apply those changes

