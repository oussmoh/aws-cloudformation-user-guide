# AWS::AppFlow::Flow AggregationConfig<a name="aws-properties-appflow-flow-aggregationconfig"></a>

 The aggregation settings that you can use to customize the output format of your flow data\. 

## Syntax<a name="aws-properties-appflow-flow-aggregationconfig-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-appflow-flow-aggregationconfig-syntax.json"></a>

```
{
  "[AggregationType](#cfn-appflow-flow-aggregationconfig-aggregationtype)" : String,
  "[TargetFileSize](#cfn-appflow-flow-aggregationconfig-targetfilesize)" : Integer
}
```

### YAML<a name="aws-properties-appflow-flow-aggregationconfig-syntax.yaml"></a>

```
  [AggregationType](#cfn-appflow-flow-aggregationconfig-aggregationtype): String
  [TargetFileSize](#cfn-appflow-flow-aggregationconfig-targetfilesize): Integer
```

## Properties<a name="aws-properties-appflow-flow-aggregationconfig-properties"></a>

`AggregationType`  <a name="cfn-appflow-flow-aggregationconfig-aggregationtype"></a>
 Specifies whether Amazon AppFlow aggregates the flow records into a single file, or leave them unaggregated\.   
*Required*: No  
*Type*: String  
*Allowed values*: `None | SingleFile`  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`TargetFileSize`  <a name="cfn-appflow-flow-aggregationconfig-targetfilesize"></a>
The desired file size, in MB, for each output file that Amazon AppFlow writes to the flow destination\. For each file, Amazon AppFlow attempts to achieve the size that you specify\. The actual file sizes might differ from this target based on the number and size of the records that each file contains\.  
*Required*: No  
*Type*: Integer  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

## See also<a name="aws-properties-appflow-flow-aggregationconfig--seealso"></a>
+ [AggregationConfig](https://docs.aws.amazon.com/appflow/1.0/APIReference/API_AggregationConfig.html) in the *Amazon AppFlow API Reference*\.

