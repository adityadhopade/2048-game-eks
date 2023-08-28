### Command to configure IAM OIDC Provider

## Check if the IAM OIDC provider configured already

```
aws iam list-open-id-connect-providers | grep $oidc_id | cut -d "/" -f4\n
```

If not run the below command

```
eksctl utils associate-iam-oidc-provider --cluster 2048-cluster --approve
```