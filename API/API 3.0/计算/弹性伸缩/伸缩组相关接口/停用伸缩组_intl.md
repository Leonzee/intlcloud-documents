## 1. API Description

Domain name for API request: as.tencentcloudapi.com.

This API (DisableAutoScalingGroup) is used to disable a scaling group.

Default request rate limit: 20/sec.

Note: This API supports Finance regions. Finance and non-Finance regions are isolated from each other. Therefore, if the common parameter `Region` is a Finance region (such as ap-shanghai-fsi), you need to specify a domain name containing the Finance region specified in the Region field, for example: as.ap-shanghai-fsi.tencentcloudapi.com.



## 2. Input Parameters

The following request parameter list only provides API request parameters and some common parameters. For the complete common parameter list, see [Common Request Parameters](/document/api/377/20426).

| Parameter Name | Required | Type | Description |
|---------|---------|---------|---------|
| Action | Yes | String | Common parameter. The value​ used for this API: DisableAutoScalingGroup |
| Version | Yes | String | Common parameter. The value used for this API: 2018-04-19 |
| Region | Yes | String | Common parameter. For more information, see the [list of regions](/document/api/377/20426#.E5.9C.B0.E5.9F.9F.E5.88.97.E8.A1.A8) supported by the product. |
| AutoScalingGroupId | Yes | String | Scaling group ID |

## 3. Output Parameters

| Parameter Name | Type | Description |
|---------|---------|---------|
| RequestId | String | The unique ID of a request, which is required for each troubleshooting case. |

## 4. Example

### Example 1 Disable a scaling group

#### Input example

```
https://as.tencentcloudapi.com/?Action=DisableAutoScalingGroup
&AutoScalingGroupId=asg-nvnlpbb8
&<Common request parameters>
```

#### Output example

```
{
  "Response": {
    "RequestId": "aa9ead18-44c8-42a8-a68b-ac6206969c2c"
  }
}
```


## 5. Resources for Developers

### API Explorer

**This tool allows online call, signature authentication, SDK code generation and quick indexing of APIs to greatly improve the efficiency of using cloud APIs.**

* [API 3.0 Explorer](https://console.cloud.tencent.com/api/explorer?Product=as&Version=2018-04-19&Action=DisableAutoScalingGroup)

### SDK

Cloud API 3.0 comes with the software development kit (SDK) that supports multiple programming languages and makes it easier to call the APIs.

* [Tencent Cloud SDK 3.0 for Python](https://github.com/TencentCloud/tencentcloud-sdk-python)
* [Tencent Cloud SDK 3.0 for Java](https://github.com/TencentCloud/tencentcloud-sdk-java)
* [Tencent Cloud SDK 3.0 for PHP](https://github.com/TencentCloud/tencentcloud-sdk-php)
* [Tencent Cloud SDK 3.0 for Go](https://github.com/TencentCloud/tencentcloud-sdk-go)
* [Tencent Cloud SDK 3.0 for NodeJS](https://github.com/TencentCloud/tencentcloud-sdk-nodejs)
* [Tencent Cloud SDK 3.0 for .NET](https://github.com/TencentCloud/tencentcloud-sdk-dotnet)

### Command line tools

* [Tencent Cloud CLI 3.0](https://cloud.tencent.com/document/product/440/6176)

## 6. Error Codes

The following only lists the error codes related to this API. For other error codes, see [Common Error Codes](/document/api/377/20428#.E5.85.AC.E5.85.B1.E9.94.99.E8.AF.AF.E7.A0.81).

| Error Code | Description |
|---------|---------|
| InternalError | Internal error |
| ResourceNotFound.AutoScalingGroupIdNotFound | The scaling group does not exist |

