# microservice-azure

Deploy microservice to Azure

- Simple REST, Azure, AKS, Kubernetes

# RUN

docker run -it --rm -p 3000:80 --name microservicecontainer microservice

or

docker ps

Serves JSON on http://localhost:3000/WeatherForecast

# Deployment

- Push docker image
- Setup Azure and Kubernetes Azure
- Create Resource group
- Create AKS cluster
- Download credentials to deploy to AKS cluster and deploy
- Create yaml for deployment and apply
