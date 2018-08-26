---
name: VictorOps
x-slug: victorops
description: VictorOps incident managament software gives DevOps observability, collaboration,
  & real-time alerting, to build, deploy, & operate software. Learn more.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
x-kinRank: "8"
x-alexaRank: "196587"
tags: Oncall
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apis.md
specificationVersion: "0.14"
apis:
- name: Victor Ops - Get an organization's on-call users
  x-api-slug: apipublicv1oncallcurrent-get
  description: |-
    Get all on-call uesrs/teams for your organization.

    This API may be called a maximum of 1 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Orchestration, Stack Network, Technology, SaaS, Enterprise, internet, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1oncallcurrent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1oncallcurrent-get-openapi.md
- name: Victor Ops - Create an on-call override (take on-call)
  x-api-slug: apipublicv1policiespolicyoncalluser-patch
  description: |-
    Replaces a currently on-call user in the escalation policy with another.  In many cases, the policy slug
    will match the slug of the team that contains it.

    This API may be called a maximum of 6 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Orchestration, Stack Network, Technology, SaaS, Enterprise, internet, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1policiespolicyoncalluser-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1policiespolicyoncalluser-patch-openapi.md
- name: Victor Ops - Get a team's on-call schedule
  x-api-slug: apipublicv1teamteamoncallschedule-get
  description: |-
    __NOTE: This call is deprecated. Please use `GET /api-public/v2/team/{team}/oncall/schedule`.__

    Get the on-call schedule for a team, including on-call overrides.

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Orchestration, Stack Network, Technology, SaaS, Enterprise, internet, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1teamteamoncallschedule-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1teamteamoncallschedule-get-openapi.md
- name: Victor Ops - Create an on-call override (take on-call)
  x-api-slug: apipublicv1teamteamoncalluser-patch
  description: |-
    __NOTE: This API call is deprecated. Please use `PATCH /api-public/v2/policies/{policy}/oncall/user`__

    Replaces a currently on-call user on the team with another.

    This API may be called a maximum of 6 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Orchestration, Stack Network, Technology, SaaS, Enterprise, internet, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1teamteamoncalluser-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1teamteamoncalluser-patch-openapi.md
- name: Victor Ops - Get a user's on-call schedule
  x-api-slug: apipublicv1useruseroncallschedule-get
  description: |-
    __NOTE: This call is deprecated. Please use `GET /api-public/v2/user/{user}/oncall/schedule`.__

    Get the on-call schedule for a user for all teams, including on-call overrides.

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Orchestration, Stack Network, Technology, SaaS, Enterprise, internet, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1useruseroncallschedule-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv1useruseroncallschedule-get-openapi.md
- name: Victor Ops - Get a team's on-call schedule
  x-api-slug: apipublicv2teamteamoncallschedule-get
  description: |-
    Get the on-call schedule for a team, including on-call overrides.

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Orchestration, Stack Network, Technology, SaaS, Enterprise, internet, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv2teamteamoncallschedule-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv2teamteamoncallschedule-get-openapi.md
- name: Victor Ops - Get a user's on-call schedule
  x-api-slug: apipublicv2useruseroncallschedule-get
  description: |-
    Get the on-call schedule for a user for all teams the user is on, including on-call overrides.

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Orchestration, Stack Network, Technology, SaaS, Enterprise, internet, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv2useruseroncallschedule-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apipublicv2useruseroncallschedule-get-openapi.md
- name: Victor Ops - A list of shift changes for a team
  x-api-slug: apireportingv1teamteamoncalllog-get
  description: |-
    Returns a log of user shift changes for the specified team. This is historical
    data, and may be up to 15 minutes behind real-time log data.

    This API may be called a maximum of 6 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Orchestration, Stack Network, Technology, SaaS, Enterprise, internet, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apireportingv1teamteamoncalllog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oncall/master/_listings/victorops/apireportingv1teamteamoncalllog-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://vestorly.api.gallery.streamdata.io
- type: x-api-stack
  url: http://victorops.stack.network
- type: x-blog
  url: https://victorops.com/blog/
- type: x-blog-rss
  url: https://victorops.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/victorops
- type: x-email
  url: support@victorops.com
- type: x-email
  url: info@victorops.com
- type: x-email
  url: press@victorops.com
- type: x-email
  url: sales@victorops.com
- type: x-github
  url: https://github.com/victorops
- type: x-openapi
  url: https://portal.victorops.com/api-docs/victorops-api-v1.yaml
- type: x-pricing
  url: https://victorops.com/pricing/
- type: x-twitter
  url: https://twitter.com/VictorOps
- type: x-website
  url: http://victorops.com
- type: x-website
  url: https://victorops.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---