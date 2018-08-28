swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 1
info:
  title: CommerceAPI
  version: 1.0.0
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Inventory/{partnerId}/Item/{sku}:
    get:
      summary: Get a single item by SKU
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Inventory_GetItem
      x-api-path-slug: apiv1inventorypartneriditemsku-get
      parameters:
      - in: path
        name: partnerId
        description: Partner account number
      - in: path
        name: sku
        description: Item SKU
      responses:
        200:
          description: OK
      tags:
      - Single
      - Item
      - By
      - SKU
  /api/v1/Inventory/{partnerId}/Matching:
    delete:
      summary: Delete all SKU mappings.
      description: Request rate limited to 1 request every 60 seconds with bursts
        up to 2 requests.
      operationId: Inventory_DeleteMappings
      x-api-path-slug: apiv1inventorypartneridmatching-delete
      parameters:
      - in: path
        name: partnerId
        description: Partner account number
      responses:
        200:
          description: OK
      tags:
      - SKU
      - Mappings