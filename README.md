# helm-7dtd
Helm Chart to deploy a 7 days to die server in a Kubernetes cluster. 

### Config
Feel free to modify values.yaml before installation

values.yaml options:

https://github.com/vinanrra/Docker-7DaysToDie/blob/master/docs/parameters.md#7-days-to-die


### Install
`helm install 7daystodie . -f values.yaml --namespace 7days --create-namespace`

### Notes
docker version of 7dtd pulled from:

https://github.com/vinanrra/Docker-7DaysToDie 
https://hub.docker.com/r/vinanrra/7dtd-server 