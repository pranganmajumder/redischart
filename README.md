##### How to create & install a chart on local machine :
* The was created through `helm create redischart`
* Copied the necessary file from bitnami chart to this chart
* Install the chart `helm install <release-name> ./redischart` outside redischart directory
* Now all the sts / svc / configmap will be deployed on kubernetes cluster