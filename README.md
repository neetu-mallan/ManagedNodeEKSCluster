# ManagedNodeEKSCluster

This repo helps in creating a EKS Cluster using Managed(EC2) Nodes.
We need to create 2 IAM roles-
1. For the Cluster
2. For the Nodes, so that they can interact with other AWS services/resources.
Finally to test the successful creation, we need to deploy an application on the cluster nodes & access them through the Load Balancer External IP
