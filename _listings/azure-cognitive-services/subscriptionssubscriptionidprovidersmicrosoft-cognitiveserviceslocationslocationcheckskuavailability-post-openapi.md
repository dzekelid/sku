---
swagger: "2.0"
x-collection-name: Azure Cognitive Services
x-complete: 0
info:
  title: Azure Cognitive Services Check Sku Availability List
  description: Check available SKUs.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.CognitiveServices/locations/{location}/checkSkuAvailability:
    post:
      summary: Check Sku Availability List
      description: Check available SKUs.
      operationId: CheckSkuAvailability_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-cognitiveserviceslocationslocationcheckskuavailability-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Check SKU Availablity POST body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
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