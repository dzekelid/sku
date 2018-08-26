---
swagger: "2.0"
x-collection-name: Azure Cognitive Services
x-complete: 1
info:
  title: CognitiveServicesManagementClient
  description: cognitive-services-management-client
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
---