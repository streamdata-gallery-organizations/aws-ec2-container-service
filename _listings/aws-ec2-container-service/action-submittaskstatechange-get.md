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
  /?Action=SubmitTaskStateChange:
    get:
      summary: ' Submit Task State Change '
      description: This action is only used by the Amazon EC2 Container Service agent,
        and it is not intended for use outside of the agent
      operationId: submitTaskStateChange
      responses:
        200:
          description: OK
      tags:
      - task state change
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