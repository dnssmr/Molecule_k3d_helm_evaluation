## Molecule Evaluation

This is a little Ansible Role which installes the kubernetes dashboard via helm in an existing cluster. I wrote a small molecule POC to test the functionality of the role.  
Molecule creates a k3d cluster on the local machine, lets the role run onto it, and test if the wanted pods are in the cluster. Then the cluster will be deleted.