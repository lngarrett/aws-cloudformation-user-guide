# Amazon S3 Bucket LifecycleConfiguration<a name="aws-properties-s3-bucket-lifecycleconfig"></a>

Describes the lifecycle configuration for objects in an [ AWS::S3::Bucket](aws-properties-s3-bucket.md) resource\.

## Syntax<a name="w13ab1c21c10d204c13c74b5"></a>

### JSON<a name="aws-properties-s3-bucket-lifecycleconfig-syntax.json"></a>

```
{
  "[Rules](#cfn-s3-bucket-lifecycleconfig-rules)" : [ Lifecycle Rule, ... ]
}
```

### YAML<a name="aws-properties-s3-bucket-lifecycleconfig-syntax.yaml"></a>

```
[Rules](#cfn-s3-bucket-lifecycleconfig-rules):
  - Lifecycle Rule
```

## Properties<a name="w13ab1c21c10d204c13c74b7"></a>

`Rules`  <a name="cfn-s3-bucket-lifecycleconfig-rules"></a>
A lifecycle rule for individual objects in an S3 bucket\.  
*Required*: Yes  
*Type*: [Rule](aws-properties-s3-bucket-lifecycleconfig-rule.md)