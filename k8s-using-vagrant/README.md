# k8s-using-vagrant

Setup Kubernetes cluster using Vagrant

```sh
vagrant up
```

Note: the vagrant script installs the followings automatically for the dynamic provisioning of the persistent volume using NFS provisioner.

- NFS server on the master node
- NFS client on the worker nodes
