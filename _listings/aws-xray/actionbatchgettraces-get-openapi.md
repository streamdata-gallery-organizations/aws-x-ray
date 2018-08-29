---
swagger: "2.0"
x-collection-name: AWS X-Ray
x-complete: 0
info:
  title: AWS X-Ray API Batch Get Traces
  version: 1.0.0
  description: Retrieves a list of traces specified by ID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=BatchGetTraces:
    get:
      summary: Batch Get Traces
      description: Retrieves a list of traces specified by ID.
      operationId: batchGetTraces
      x-api-path-slug: actionbatchgettraces-get
      parameters:
      - in: query
        name: NextToken
        description: Pagination token
        type: string
      - in: query
        name: TraceIds
        description: Specify the trace IDs of requests for which to retrieve segments
        type: string
      responses:
        200:
          description: OK
      tags:
      - Traces
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