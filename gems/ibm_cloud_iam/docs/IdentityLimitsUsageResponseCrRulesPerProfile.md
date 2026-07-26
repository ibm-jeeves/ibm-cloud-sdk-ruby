# IbmCloudIam::IdentityLimitsUsageResponseCrRulesPerProfile

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **limit** | **Integer** | Maximum allowed compute resource rules per profile |  |
| **profiles** | [**Array&lt;ProfileCount&gt;**](ProfileCount.md) | List of profiles with their compute resource rules usage counts | [optional] |

## Example

```ruby
require 'ibm_cloud_iam'

instance = IbmCloudIam::IdentityLimitsUsageResponseCrRulesPerProfile.new(
  limit: null,
  profiles: null
)
```

