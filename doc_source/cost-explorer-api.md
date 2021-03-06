# Using the AWS Cost Explorer API<a name="cost-explorer-api"></a>

The Cost Explorer API allows you to programmatically query your cost and usage data\. You can query for aggregated data such as total monthly costs or total daily usage\. You can also query for granular data, such as the number of daily write operations for DynamoDB database tables in your production environment\. 

If you use a programming language for which AWS provides an SDK, we recommend that you use the SDK\. All the AWS SDKs greatly simplify the process of signing requests and save you a significant amount of time when compared with using the Price List Service API\. In addition, the SDKs integrate easily with your development environment and provide easy access to related commands\.

For more information about available SDKs, see [Tools for Amazon Web Services](https://aws.amazon.com/tools)\. For more information about the AWS Cost Explorer API, see the [AWS Billing and Cost Management API Reference](http://docs.aws.amazon.com/aws-cost-management/latest/APIReference/)\.

## Service Endpoint<a name="ce-endpoint"></a>

Service Endpoint

The Cost Explorer API provides the following endpoint:
+ https://ce\.us\-east\-1\.amazonaws\.com

## Granting IAM Permissions to Use the AWS Cost Explorer API<a name="ce-iam"></a>

An IAM user must be granted explicit permission to query the AWS Cost Explorer API\. For the policy that grants the necessary permissions to an IAM user, see [Example 12: View costs and usage](billing-permissions-ref.md#example-policy-ce-api)\. 