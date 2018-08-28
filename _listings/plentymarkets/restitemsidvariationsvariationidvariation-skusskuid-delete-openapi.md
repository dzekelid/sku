---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Delete an SKU
  description: Deletes an SKU. The ID of the SKU must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/items/{id}/variations/{variationId}/variation_additional_skus:
    post:
      summary: Create an additional SKU
      description: Creates an additional SKU. The ID of the variation must be specified.
      operationId: postRestItemsVariationsVariationVariationAdditionalSkus
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skus-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_additional_skus
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Additional
      - SKU
  /rest/items/{id}/variations/{variationId}/variation_additional_skus/{additionalSkuId}:
    delete:
      summary: Delete an additional SKU
      description: Deletes an additional SKU. The ID of the additional SKU must be
        specified.
      operationId: deleteRestItemsVariationsVariationVariationAdditionalSkusAdditionalsku
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-delete
      parameters:
      - in: path
        name: additionalSkuId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Additional
      - SKU
    get:
      summary: Gets an additional SKU
      description: Gets an additional SKU. The ID of the additional SKU must be specified.
      operationId: getRestItemsVariationsVariationVariationAdditionalSkusAdditionalsku
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-get
      parameters:
      - in: path
        name: additionalSkuId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Additional
      - SKU
    put:
      summary: Update an additional SKU
      description: Updates an additional SKU. The ID of the additional SKU must be
        specified.
      operationId: putRestItemsVariationsVariationVariationAdditionalSkusAdditionalsku
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_additional_skus/{additionalSkuId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: additionalSkuId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Additional
      - SKU
  /rest/items/{id}/variations/{variationId}/variation_skus:
    post:
      summary: Create an SKU
      description: Creates an SKU. The ID of the variation must be specified.
      operationId: postRestItemsVariationsVariationVariationSkus
      x-api-path-slug: restitemsidvariationsvariationidvariation-skus-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_skus
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - SKU
  /rest/items/{id}/variations/{variationId}/variation_skus/{skuId}:
    delete:
      summary: Delete an SKU
      description: Deletes an SKU. The ID of the SKU must be specified.
      operationId: deleteRestItemsVariationsVariationVariationSkusSku
      x-api-path-slug: restitemsidvariationsvariationidvariation-skusskuid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: skuId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - SKU
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