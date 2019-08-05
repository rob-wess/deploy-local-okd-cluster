# deploy-local-okd-cluster
Deploy local Openshift Origin Cluster with Ansible

Created for CentOS 7
- Reference: https://computingforgeeks.com/setup-openshift-origin-local-cluster-on-centos/ 

After ansible plays complete, switch user to docker and cd ~/

Run `oc cluster up --public-hostname=<Public IP>`
