swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 1
info:
  title: Broadleaf Commerce API
  description: the-default-broadleaf-commerce-apis
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
  /catalog/sku/{skuId}/media:
    get:
      summary: Get Catalog Sku Skuid Media
      description: Get catalog sku skuid media.
      operationId: getCatalogSkuSkuMedia
      x-api-path-slug: catalogskuskuidmedia-get
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
      - Media