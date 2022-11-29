# helm-infra


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

Install helm chart 

move outside the helm chart directory 
 cd ../

 ```
helm dependency build
```

```
helm install infra .
```


## File Structure

### dependcy

install dependencies EFK, Prometheus, etc


