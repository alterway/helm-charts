# aks-helloworld

Simple aks-helloworld chart.

## Installing the Chart

Add the Azure Samples chart repository.

```
helm repo add alterway https://alterway.github.io/helm-charts
```

Install the chart.

```
helm install alterway/aks-helloworld
```


## Configuration

The following tables lists the configurable parameters of the azure-vote chart and the default values.

| Parameter | Description | Default |
|---|---|---|
| title | Title for hello world app. | Azure Vote App |
| serviceName | Name for Kubernetes service. | aks-helloworld |
| serviceType | Type for Kubernetes service. | ClusterIP |