---
page_title: "jamfpro_self_service_plus_settings"
description: |-
  
---

# jamfpro_self_service_plus_settings (Resource)


## Example Usage
```terraform
resource "jamfpro_self_service_plus_settings" "example" {
  enabled = true
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `enabled` (Boolean) Use Self Service+ as the default end user application (Selecting this option uninstalls Self Service classic from end user devices).

### Optional

- `timeouts` (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))

### Read-Only

- `id` (String) The ID of this resource.

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- `create` (String)
- `delete` (String)
- `read` (String)
- `update` (String)