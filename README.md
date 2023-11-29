# docker-kubernetes
This is simple rep to deploy docker image to kuberntes cluster

Step-1 Create or build a docker image using Dockerfile
    docker build -t tomcat-boxer .
step-2 push the image to dockerhub
    # Attach the tag before pusging to dockerhub
    docker tag tomcat-boxer:latest krishnamsg/tomcat-boxer:latest
    docker push krishnamsg/tomcat-boxer:latest
step-3 

