# AWS::EKS::Cluster Provider<a name="aws-properties-eks-cluster-provider"></a>

Identifies the AWS Key Management Service \(AWS KMS\) key used to encrypt the secrets\.

## Syntax<a name="aws-properties-eks-cluster-provider-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-eks-cluster-provider-syntax.json"></a>

```
{
  "[KeyArn](#cfn-eks-cluster-provider-keyarn)" : String
}
```

### YAML<a name="aws-properties-eks-cluster-provider-syntax.yaml"></a>

```
  [KeyArn](#cfn-eks-cluster-provider-keyarn): String
```

## Properties<a name="aws-properties-eks-cluster-provider-properties"></a>

`KeyArn`  <a name="cfn-eks-cluster-provider-keyarn"></a>
Amazon Resource Name \(ARN\) or alias of the KMS key\. The KMS key must be symmetric, created in the same region as the cluster, and if the KMS key was created in a different account, the user must have access to the KMS key\. For more information, see [Allowing Users in Other Accounts to Use a KMS key](https://docs.aws.amazon.com/kms/latest/developerguide/key-policy-modifying-external-accounts.html) in the * AWS Key Management Service Developer Guide*\.  
*Required*: No  
*Type*: String  
*Update requires*: [Replacement](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-replacement)