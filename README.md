# K8s
Deploy a containerized application to Kubernetes using helm
1. node:
    a. build a node application and dockerize it 1st. 
        [- docker build -t my-node-app .
         - docker run -p 3000:3000 my-node-app]
    b. push the dockerised container to artifact(dockerhub) so that minikube can access it.
        [- docker login
         - docker tag my-node-app:latest dishadgithub/node-application:0.0.1
         - docker push dishadgithub/node-application:0.0.1]
