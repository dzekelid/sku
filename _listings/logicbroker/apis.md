---
name: Logicbroker
x-slug: logicbroker
description: Logicbroker provides beautiful technology that unites brands, retailers,
  and the systems they rely on. Harness the latest in cloud and supply chain automation
  technology with unrivaled speed and integration flexibility. We craft the connections
  that enable digital commerce.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logicbroker-logo.png
x-kinRank: "7"
x-alexaRank: ""
tags: SKU
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sku/master/_listings/logicbroker/apis.md
specificationVersion: "0.14"
apis:
- name: CommerceAPI - Get a single item by SKU
  x-api-slug: apiv1inventorypartneriditemsku-get
  description: Request rate limited to 10 requests per second with bursts up to 100
    requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logicbroker-logo.png
  humanURL: https://www.logicbroker.com/
  baseURL: https://stage.commerceapi.io//
  tags: Commerce, Retail
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sku/master/_listings/logicbroker/apiv1inventorypartneriditemsku-get-openapi.md
- name: CommerceAPI - Delete all SKU mappings.
  x-api-slug: apiv1inventorypartneridmatching-delete
  description: Request rate limited to 1 request every 60 seconds with bursts up to
    2 requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logicbroker-logo.png
  humanURL: https://www.logicbroker.com/
  baseURL: https://stage.commerceapi.io//
  tags: Commerce, Retail
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sku/master/_listings/logicbroker/apiv1inventorypartneridmatching-delete-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.logicbroker.com/feed/
- type: x-developer
  url: https://dev.logicbroker.com/
- type: x-openapi
  url: https://stage.commerceapi.io/swagger/docs/v1
- type: x-api-gallery
  url: http://kentico.cloud.api.gallery.streamdata.io
- type: x-documentation
  url: https://stage.commerceapi.io/swagger/ui/index
- type: x-website
  url: https://www.logicbroker.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---