---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 1
info:
  title: API title
  version: 1.0.0
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
---