---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get accessible project type by key
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/project/type/{projectTypeKey}/accessible:
    get:
      summary: Get accessible project type by key
      description: |-
        Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
      operationId: com.atlassian.jira.rest.v2.project.type.ProjectTypeResource.getAccessibleProjectTypeByKey_get
      x-api-path-slug: api2projecttypeprojecttypekeyaccessible-get
      parameters:
      - in: path
        name: projectTypeKey
        description: The key of the project type
      responses:
        200:
          description: OK
      tags:
      - Accessible
      - Project
      - Type
      - By
      - Key
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