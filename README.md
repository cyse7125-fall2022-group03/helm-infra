# helm-infra

## Chart Info
Contains dependency charts for the following:
1. Prometheus
2. Elastic Search
3. Metrics Server
4. Grafana
5. Kibana
6. Kafka (& Zookeeper)
7. Fluentd



| Name                | NUID      | Email                          |
| ------------------- | --------- | ------------------------------ |
| Ketki Kule          | 001549838 | kule.k@northeastern.edu        |
| Sandeep Wagh        | 001839964 | wagh.sn@northeastern.edu       |
| Vignesh Gunasekaran | 001029530 | gunasekaran.v@northeastern.edu |

install dependencies EFK, Prometheus, etc

## Validate helm chart
cd app

```
helm lint . 
```

```
helm template .
```

## Installation 

move outside the helm chart directory 
 cd ../

```
helm dependency build
```

```
helm install infra .
```

## To check Prometheus locally 

```
kubectl port-forward service/infra-prometheus-server 9092:80
```

