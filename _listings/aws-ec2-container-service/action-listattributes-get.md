---
swagger: "2.0"
info:
  title: AWS EC2 Container Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListAttributes:
    get:
      summary: ' List Attributes '
      description: |-
        Lists the attributes for Amazon ECS resources within a specified target type and
                    cluster
      operationId: listAttributes
      parameters:
      - in: query
        name: attributeName
        description: The name of the attribute with which to filter the results
        type: string
      - in: query
        name: attributeValue
        description: The value of the attribute with which to filter results
        type: string
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          to list attributes
        type: string
      - in: query
        name: maxResults
        description: The maximum number of cluster results returned by ListAttributes
          in            paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated                ListAttributes
          request where maxResults was used and the            results exceeded the
          value of that parameter
        type: string
      - in: query
        name: targetType
        description: The type of the target with which to list attributes
        type: string
      responses:
        200:
          description: OK
      tags:
      - attributes
definitions: []
x-collection-name: AWS EC2 Container Service
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