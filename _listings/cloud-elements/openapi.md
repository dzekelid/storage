swagger: "2.0"
x-collection-name: Cloud Elements
x-complete: 1
info:
  title: zohocrm
  version: api-v2
host: console.cloud-elements.com
basePath: /elements/api-v2/hubs/crm
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reports/get_storage:
    post:
      summary: Get Storage
      description: Get storage.
      operationId: postReportsGetStorage
      x-api-path-slug: reportsget-storage-post
      parameters:
      - in: query
        name: end_date
        description: optional ending date (exclusive)
      - in: query
        name: start_date
        description: optional starting date (inclusive)
      responses:
        200:
          description: OK
      tags:
      - Storage