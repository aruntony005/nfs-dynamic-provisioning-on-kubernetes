# nfs-dynamic-provisioning-on-kubernetes

-> In the nfs server change the ownership
chown -R nobody: nfs

-> Install the below in the kubernetes cluster.
yum install nfs-utils nfs4-acl-tools -y
