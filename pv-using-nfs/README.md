# pv-using-nfs
Setup a default StorageClass that supports the dynamic provisioniong of PV (Persistent Volume) using NFS provisioner.

## Prerequisites

- NFS server should be installed on the master node.
- NFS client should be installed on all worker nodes.

## Deployment

```sh
kubectl create -f class.yaml
kubectl create -f rbac.yaml
kubectl create -f deployment.yaml
```
