---
swagger: "2.0"
x-collection-name: VictorOps
x-complete: 0
info:
  title: Victor Ops Get a user's on-call schedule
  description: |-
    __NOTE: This call is deprecated. Please use `GET /api-public/v2/user/{user}/oncall/schedule`.__

    Get the on-call schedule for a user for all teams, including on-call overrides.

    This API may be called a maximum of 15 times per minute.
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
  /api-public/v1/policies/{policy}/oncall/user:
    patch:
      summary: Create an on-call override (take on-call)
      description: |-
        Replaces a currently on-call user in the escalation policy with another.  In many cases, the policy slug
        will match the slug of the team that contains it.

        This API may be called a maximum of 6 times per minute.
      operationId: api_public.v1.policies.policy.oncall.user.patch
      x-api-path-slug: apipublicv1policiespolicyoncalluser-patch
      parameters:
      - in: query
        name: No Name
      - in: path
        name: policy
        description: The VictorOps policy slug
      responses:
        200:
          description: OK
      tags:
      - Policies
      - Policy
      - Oncall
      - User
  /api-public/v1/team/{team}/oncall/schedule:
    get:
      summary: Get a team's on-call schedule
      description: |-
        __NOTE: This call is deprecated. Please use `GET /api-public/v2/team/{team}/oncall/schedule`.__

        Get the on-call schedule for a team, including on-call overrides.

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.team.team.oncall.schedule.get
      x-api-path-slug: apipublicv1teamteamoncallschedule-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: team
        description: The VictorOps team slug
      responses:
        200:
          description: OK
      tags:
      - Team
      - Team
      - Oncall
      - Schedule
  /api-public/v1/team/{team}/oncall/user:
    patch:
      summary: Create an on-call override (take on-call)
      description: |-
        __NOTE: This API call is deprecated. Please use `PATCH /api-public/v2/policies/{policy}/oncall/user`__

        Replaces a currently on-call user on the team with another.

        This API may be called a maximum of 6 times per minute.
      operationId: api_public.v1.team.team.oncall.user.patch
      x-api-path-slug: apipublicv1teamteamoncalluser-patch
      parameters:
      - in: query
        name: No Name
      - in: path
        name: team
        description: The VictorOps team slug
      responses:
        200:
          description: OK
      tags:
      - Team
      - Team
      - Oncall
      - User
  /api-public/v1/user/{user}/oncall/schedule:
    get:
      summary: Get a user's on-call schedule
      description: |-
        __NOTE: This call is deprecated. Please use `GET /api-public/v2/user/{user}/oncall/schedule`.__

        Get the on-call schedule for a user for all teams, including on-call overrides.

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.user.user.oncall.schedule.get
      x-api-path-slug: apipublicv1useruseroncallschedule-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: user
        description: The VictorOps user ID
      responses:
        200:
          description: OK
      tags:
      - User
      - User
      - Oncall
      - Schedule
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