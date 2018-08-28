swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscribedSkus/{id}:
    get:
      summary: Get Subscribed Sku
      description: Get subscribedSku Retrieve a specific commercial subscription that
        an organization has acquired.
      operationId: GetSubscribedSku
      x-api-path-slug: subscribedskusid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer token
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subscribed
      - Sku