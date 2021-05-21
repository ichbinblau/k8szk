# Kubernetes ZooKeeper K8SZK

copy from retired [kubernetis/contrib statefulset zookeeper](https://github.com/kubernetes-retired/contrib/tree/master/statefulsets/zookeeper) 

used to build a replacement image for `gcr.io/google_samples/k8szk:v3` in order to enable kerberos

Differences from google samples image:

* Add jaas.conf to zookeeper conf dir 
* Update zkGenConfig.sh in order to update java.env and zoo.cfg


Please refer to the [README_ORIGINAL.md]() for more details.
