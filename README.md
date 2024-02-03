# dotnet-docker
.NET Tutorial - First Microservice with docker

## How to run
1. Create Docker Images
   `docker build -t mymicroservice:<version> .`
2. Run Docker Image
   `docker run -it --rm -p 3000:8080 --name mymicroservicecontainer mymicroservice:<version>`
## References
- https://dotnet.microsoft.com/en-us/learn/aspnet/microservice-tutorial/intro
