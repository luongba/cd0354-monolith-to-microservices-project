# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
![image](https://github.com/luongba/cd0354-monolith-to-microservices-project/blob/main/screenshots/docker_hub.png))

* Deploy to Docker Hub / build-and-deploy
  ![image](https://github.com/luongba/cd0354-monolith-to-microservices-project/blob/main/screenshots/git_cicd.png)


## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
