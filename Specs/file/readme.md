# Storage Dataplane

> see https://aka.ms/autorest

``` yaml
azure-validator: true
openapi-type: data-plane

directive:
  # These directives are suppressed because they should be ignored.
  - suppress: R3016
  - suppress: R2058

  # These directives are temporaryily suppressed. They should be removed from this file before Swaggers can be used to generate documentation. The Swaggers can still be used to generate code with these directives suppressed. Tracking with work item #2181761.
  - suppress: R2022 # Add x-ms-examples
  - suppress: R2003 # etag / url is not a known format
  - suppress: R4000 # Missing description
  - suppress: R4001 # url defined in global param without extension

```