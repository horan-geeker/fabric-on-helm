## fabric on helm

### start

* cd /path/to/fabric-on-helm
* helm install ./helm

## attention

* make sure orderer startup after kafka cluster, if not delete orderer pod and it will auto restart pod, the orderer log will show `Start phase completed successfully` if start success

## other

* use k8s without helm deploy fabric here https://github.com/horan-geeker/fabric-on-k8s
