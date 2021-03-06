# AWS::LicenseManager::License Filter<a name="aws-properties-licensemanager-license-filter"></a>

A filter name and value pair that is used to return more specific results from a describe operation\. Filters can be used to match a set of resources by specific criteria, such as tags, attributes, or IDs\.

## Syntax<a name="aws-properties-licensemanager-license-filter-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-licensemanager-license-filter-syntax.json"></a>

```
{
  "[Name](#cfn-licensemanager-license-filter-name)" : String,
  "[Values](#cfn-licensemanager-license-filter-values)" : StringList
}
```

### YAML<a name="aws-properties-licensemanager-license-filter-syntax.yaml"></a>

```
  [Name](#cfn-licensemanager-license-filter-name): String
  [Values](#cfn-licensemanager-license-filter-values): 
    StringList
```

## Properties<a name="aws-properties-licensemanager-license-filter-properties"></a>

`Name`  <a name="cfn-licensemanager-license-filter-name"></a>
Name of the filter\. Filter names are case\-sensitive\.  
*Required*: Yes  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`Values`  <a name="cfn-licensemanager-license-filter-values"></a>
Filter values\. Filter values are case\-sensitive\.  
*Required*: Yes  
*Type*: [StringList](aws-properties-licensemanager-license-stringlist.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)