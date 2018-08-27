swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/branch/checkkeycodesexist:
    get:
      summary: Check specified key codes exist in branch
      description: Check specified key codes exist in branch.
      operationId: Branch_CheckKeycodesExistBykeyCodes
      x-api-path-slug: apibranchcheckkeycodesexist-get
      parameters:
      - in: query
        name: keyCodes
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Check
      - Specified
      - Key
      - Codes
      - Exist
      - In
      - Branch
  /api/property/{id}/alarms/remove:
    delete:
      summary: Remove alarm codes from a property
      description: Remove alarm codes from a property.
      operationId: Property_RemoveAlarmsByidByalarmIds
      x-api-path-slug: apipropertyidalarmsremove-delete
      parameters:
      - in: query
        name: alarmIds
        description: The ids of the alarm codes to remove
      - in: path
        name: id
        description: The property id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Alarm
      - Codes
      - From
      - Property