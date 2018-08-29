---
swagger: "2.0"
x-collection-name: AWS EC2 Container Service
x-complete: 0
info:
  title: Amazon EC2 Container Service API Create Cluster
  version: 1.0.0
  description: Creates a new Amazon ECS cluster.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateCluster:
    get:
      summary: Create Cluster
      description: Creates a new Amazon ECS cluster.
      operationId: createCluster
      x-api-path-slug: actioncreatecluster-get
      parameters:
      - in: query
        name: clusterName
        description: The name of your cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
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