## Creating the Cluster using Eks and Fargate

```
eksctl create cluster --name demo-cluster --region us-east-1 --fargate
```

## To delete the Cluster (At the End of Demo)

```
eksctl delete cluster --name demo-cluster --region us-east-1
```
