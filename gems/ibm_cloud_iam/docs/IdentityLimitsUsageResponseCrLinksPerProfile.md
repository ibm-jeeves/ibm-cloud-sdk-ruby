# IbmCloudIam::IdentityLimitsUsageResponseCrLinksPerProfile

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **limit** | **Integer** | Maximum allowed compute resource links per profile |  |
| **profiles** | [**Array&lt;ProfileCount&gt;**](ProfileCount.md) | List of profiles with their compute resource links usage counts | [optional] |

## Example

```ruby
require 'ibm_cloud_iam'

instance = IbmCloudIam::IdentityLimitsUsageResponseCrLinksPerProfile.new(
  limit: null,
  profiles: null
)
```

