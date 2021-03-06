# FabrikamFiber

This project was originally started by Richard Hundhausen and distributed on [CodePlex](https://fabrikam.codeplex.com/) as an application for training users in Visual Studio and development practices.

I have archived it here since I frequently use it for examples rebuilding existing applications to run in containers.

## Step by Step - Getting Started & Azure Service Fabric

There's a great guide on how to use this to test building Docker containers and deploying them to Azure Service Fabric [here](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-host-app-in-a-container).

If you want to try a different orchestrator, follow the steps through the first **Test your container** section, then pick from the next sections here.

If you have already built the code in Visual Studio, then you can build and run the containers with:

```powershell
docker-compose -f "C:\ignite2017\fabrikamfiber\docker-compose.yml" -f "C:\ignite2017\fabrikamfiber\docker-compose.override.yml" build
docker-compose -f "C:\ignite2017\fabrikamfiber\docker-compose.yml" -f "C:\ignite2017\fabrikamfiber\docker-compose.override.yml" up -d
```



### Kubernetes


### Docker Swarm
