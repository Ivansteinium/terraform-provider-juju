---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "juju_secret Resource - terraform-provider-juju"
subcategory: ""
description: |-
  A resource that represents a Juju secret.
---

# juju_secret (Resource)

A resource that represents a Juju secret.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `model` (String) The model in which the secret belongs.
- `value` (Map of String, Sensitive) The value map of the secret. There can be more than one key-value pair.

### Optional

- `info` (String) The description of the secret.
- `name` (String) The name of the secret.

### Read-Only

- `secret_id` (String) The ID of the secret.
