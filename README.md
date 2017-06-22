# Sonarqube 

# build the docker image
```
./build.sh
```

# deploy SonarQube to Kubernetes
```
kubectl create -f deployment.yaml 
```

based on: https://github.com/SonarSource/docker-sonarqube