---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Post Internal Two Factor Recovery Codes
  version: 1.0.0
  description: Post internal two factor recovery codes.
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/internal/two_factor_recovery_codes:
    post:
      summary: Post Internal Two Factor Recovery Codes
      description: Post internal two factor recovery codes.
      operationId: postV3InternalTwoFactorRecoveryCodes
      x-api-path-slug: v3internaltwo-factor-recovery-codes-post
      responses:
        200:
          description: OK
      tags:
      - Internal
      - Two
      - Factor
      - Recovery
      - Codes
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