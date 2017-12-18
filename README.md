ansible k8s
===========

ansible scripts used to deploy a k8s environment.

# Assumptions
  * Operating system: CentOS 7.3+ minimal
  * deployment can ssh to all nodes without password

# Roles
  * master: etcd, kube-apiserver, kube-scheduler, kube-controller-mananger
  * minion: flannel, docker, kubelet, kube-proxy

# Versions
  * kubernetes: 1.5.2
  * docker: 1.12.6
  * flannel: 0.7.1
  * etcd: 3.2.9
