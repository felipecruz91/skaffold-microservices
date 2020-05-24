# skaffold-microservices

Spinning up two microservices blazingly fast in Kubernetes with [skaffold](https://github.com/GoogleContainerTools/skaffold).

# Getting started

```cli
$> skaffold dev --port-foward
```

Visit http://localhost:9000/api/values for the `mywebapi` microservice (.NET Core Web API).

Visit http://localhost:9001/ for the `webfrontend` microservice (ASP.NET Core Web App).
