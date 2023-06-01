#Create EKS Cluster with two worker nodes using eksctl
eksctl create cluster --name demo-eks --region us-east-2 --nodegroup-name my-nodes --node-type t3.small --managed --nodes 2
