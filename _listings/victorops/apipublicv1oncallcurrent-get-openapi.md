---
swagger: "2.0"
x-collection-name: VictorOps
x-complete: 0
info:
  title: Victor Ops Get an organization's on-call users
  description: |-
    Get all on-call uesrs/teams for your organization.

    This API may be called a maximum of 1 times per minute.
  version: 0.0.2
host: api.victorops.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api-public/v1/oncall/current:
    get:
      summary: Get an organization's on-call users
      description: |-
        Get all on-call uesrs/teams for your organization.

        This API may be called a maximum of 1 times per minute.
      operationId: api_public.v1.oncall.current.get
      x-api-path-slug: apipublicv1oncallcurrent-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Oncall
      - Current
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