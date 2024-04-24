---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "alis_spanner_table Resource - alis"
subcategory: ""
description: |-
  
---

# alis_spanner_table (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `database` (String)
- `instance` (String)
- `name` (String)
- `project` (String)
- `schema` (Attributes) (see [below for nested schema](#nestedatt--schema))

<a id="nestedatt--schema"></a>
### Nested Schema for `schema`

Required:

- `columns` (Attributes List) (see [below for nested schema](#nestedatt--schema--columns))

Optional:

- `indices` (Attributes List) (see [below for nested schema](#nestedatt--schema--indices))

<a id="nestedatt--schema--columns"></a>
### Nested Schema for `schema.columns`

Required:

- `name` (String)
- `type` (String)

Optional:

- `auto_increment` (Boolean)
- `default_value` (String)
- `is_primary_key` (Boolean)
- `precision` (Number)
- `required` (Boolean)
- `scale` (Number)
- `size` (Number)
- `unique` (Boolean)


<a id="nestedatt--schema--indices"></a>
### Nested Schema for `schema.indices`

Required:

- `columns` (Set of String)
- `name` (String)

Optional:

- `unique` (Boolean)