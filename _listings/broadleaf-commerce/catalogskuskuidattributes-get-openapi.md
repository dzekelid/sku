---
swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 0
info:
  title: Broadleaf Commerce API Get Catalog Sku Skuid Attributes
  description: Get catalog sku skuid attributes.
  version: 1.0.0
host: demo.broadleafcommerce.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /catalog/product/{productId}/defaultSku:
    get:
      summary: Get Catalog Product Default sku
      description: Get catalog product default sku.
      operationId: getCatalogProductProductDefaultsku
      x-api-path-slug: catalogproductproductiddefaultsku-get
      parameters:
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
      - Default
      - Sku
  /catalog/sku/inventory:
    get:
      summary: Get Catalog Sku Inventory
      description: Get catalog sku inventory.
      operationId: getCatalogSkuInventory
      x-api-path-slug: catalogskuinventory-get
      parameters:
      - in: query
        name: id
        description: id
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Sku
      - Inventory
  /catalog/sku/{skuId}:
    get:
      summary: Get Catalog Sku Skuid
      description: Get catalog sku skuid.
      operationId: getCatalogSkuSku
      x-api-path-slug: catalogskuskuid-get
      parameters:
      - in: path
        name: skuId
        description: skuId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Sku
      - Skuid
  /catalog/sku/{skuId}/attributes:
    get:
      summary: Get Catalog Sku Skuid Attributes
      description: Get catalog sku skuid attributes.
      operationId: getCatalogSkuSkuAttributes
      x-api-path-slug: catalogskuskuidattributes-get
      parameters:
      - in: path
        name: skuId
        description: skuId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Sku
      - Skuid
      - Attributes
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---